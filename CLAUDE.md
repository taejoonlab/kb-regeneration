# kb-regeneration — LLM Wiki Obsidian Vault

## Project Overview

Bilingual (en/ko) Obsidian vault for **regeneration** research literature. The vault
started as spinal-cord-only and now spans multiple regeneration subjects. Each subject is
tracked by a **note tag** (currently `SpinalCord` and `Chondrocyte`; the source PDFs are
organized by matching **folders** on Google Drive — see *Extracted text & PDF organization*).
Each article has structured notes in both languages under `en/articles/` and `ko/articles/`.

The `Chondrocyte`-tagged notes were merged in from the former `kb-chondro` repo
(git@github.com:taejoonlab/kb-chondro.git, since retired) in 2026-07.

## Repository Structure

```
.
├── en/articles/   # English original-research notes
├── ko/articles/   # Korean original-research notes (same filenames as en/)
├── ko/reviews/    # Korean review-article notes (ko only, no en mirror)
├── extract/       # Consolidated extracted PDF text, date-stamped & split (TRACKED)
├── ko/pdf/        # PDF working dir (gitignored); ko/pdf/done/ = processed PDFs
├── tools/         # Git submodule (git@github.com:taejoonlab/kb-tools.git)
└── .obsidian/     # Obsidian config (tracked, except workspace.json)
```

원저 연구는 `articles/`에 en/ko 쌍으로, 리뷰 논문은 `ko/reviews/`에 한국어로만 작성한다. 자세한 워크플로우는 `tools/SKILL.md`(원저), `tools/SKILL_REVIEW.md`(리뷰) 참조.

## Note Format

YAML frontmatter (all notes):
```
---
tags: [YYYY-MM, <SubjectTag>]
extract: YYYY-MM-DD
extract_file: extract/YYYY-MM-DD_pNN.txt
log:
  - "YYYY-MM-DD · create · <Model> (<Tool>)"
  - "YYYY-MM-DD · edit · <Model> (<Tool>) · <what changed>"
---
```
- `tags` carries the extraction month (`YYYY-MM`) plus a **subject tag** — `SpinalCord` or
  `Chondrocyte` — that identifies which regeneration subject the note belongs to.
- `extract_file` points to the split extract part that holds this paper's source text;
  find the block inside that file by the anchor `===== <note-stem> =====`.
- `log` is the **agent change log**: an append-only YAML list, one entry per agent that
  creates or modifies the note, oldest first. Each entry is a quoted string
  `"<YYYY-MM-DD> · <action> · <Model> (<Tool>)[ · <note>]"` where `action` is `create`,
  `edit`, `rename`, `retag`, etc. Use `·` as the separator (avoid `:` so YAML stays a plain
  string list). The `log` is the machine-readable history; the human-facing provenance footer
  `*Processed by …*` still records the original authoring pass.
- Notes merged from `kb-chondro` (`Chondrocyte`, extraction month `2026-06`) do **not** yet
  have consolidated `extract/` text in this repo, so they carry no `extract_file`; their
  source PDFs live under `pdf.kb/kb-regeneration/chondro` on Google Drive.

**Original-research** note sections (en + ko):
1. `# Title` — full article title
2. `## Citation (NLM)` — NLM-formatted citation + DOI link
3. `## Background` — research background
4. `## Key Experiment Methods` — numbered methods
5. `## Results` — key findings
6. `## Perspective` — significance & future directions

**Review** notes (ko only) use a different section set — Overview / Key Topics /
Key Findings / Perspective / Key References (see `tools/SKILL_REVIEW.md`).

Every note ends with a provenance footer: `*Processed by **{LLM}** ({tool}) on {date}*`.

## PDF → Note Workflow (`tools/`)

Notes are authored from **extracted PDF text, not from the PDF directly**. Always run the
extraction script first, then work off the produced text. Full detail lives in
`tools/SKILL.md` (original research) and `tools/SKILL_REVIEW.md` (reviews); the canonical
pipeline is:

1. **Extract text first (script step).** Run the project's own extractor on the PDF —
   do not hand-roll PDF reading:
   ```bash
   pip install pymupdf            # one-time; provides the `fitz` module used by the script
   python3 tools/process_pdf.py <pdf_path> [--dry-run]
   ```
   `process_pdf.py` (a) extracts the text via `extract_text()` (PyMuPDF/`fitz`, capped at
   ~30 pages), (b) auto-detects DOI / first author / journal, (c) proposes a target filename,
   (d) flags name collisions, and (e) saves the extracted text and an MD skeleton under the
   PDF's `notes/` dir. Reuse `extract_text()` by importing it rather than re-implementing
   extraction. There is no local `pdftotext`/`poppler`; PyMuPDF (`fitz`) is the extractor.
2. **Verify filename & DOI from the extracted text (human/LLM step).** The auto-detected
   author/journal are unreliable — confirm the DOI and metadata in the extracted text and set
   the final `{FirstAuthor}{Year}_{Journal}_{Keyword}` stem yourself. Filenames can be
   mislabeled, so trust the extracted content over the existing name. Use `--dry-run` and never
   batch-rename (identical proposed names silently overwrite).
3. **Write the note from the extracted text.** Read the extracted text and fill the section
   template (original research vs review), add the subject tag, and end with the provenance footer.
4. **Consolidate & link.** Merge the per-paper extracted text into a date-stamped, ~2 MB-split
   `extract/YYYY-MM-DD_pNN.txt` with a `===== <note-stem> =====` anchor per paper, then point each
   note's `extract_file` frontmatter at the part that holds it (see below).

## Extracted text & PDF organization

- **`extract/`** (git-tracked): source PDF text consolidated per extraction date, split into
  ~2 MB parts `extract/YYYY-MM-DD_pNN.txt`. Each paper is one block delimited by
  `===== <note-stem> =====`. This is the provenance record for the notes.
- **`ko/pdf/`** (gitignored working dir): raw PDFs. Once a note is written, the PDF is moved to
  `ko/pdf/done/` (review PDFs to `ko/pdf/done/review/`), renamed to match its note stem.
  PDFs left directly under `ko/pdf/` are not yet noted (off-topic or to-review).
- `ko/pdf/notes/` holds per-file working artifacts (`*_extracted.txt`, `00_triage.md`,
  `0N_*_log.txt`) — gitignored; the committed `extract/` parts supersede the per-file extracts.
- **Google Drive** (`taejoon.kwon@gmail.com`, `pdf.kb/kb-regeneration/`): the master PDF
  archive, organized into per-subject folders — `SpinalCord/` and `chondro/`. Processed PDFs
  from the former kb-SpinalCord are under `pdf.kb/kb-regeneration/` and are being sorted into
  `SpinalCord/`; chondrocyte PDFs are under `chondro/`.

## Git Conventions

- Clone with submodules: `git clone --recurse-submodules git@github.com:taejoonlab/kb-regeneration.git`
- If already cloned without submodules: `git submodule update --init --recursive`
- Submodule URL uses **SSH** (`git@github.com:taejoonlab/kb-tools.git`) — ensure SSH key is configured
- `.gitignore` ignores: `.obsidian/workspace.json`, `.obsidian/cache/`, `.obsidian/plugins/obsidian-git/obsidian_askpass.sh`, `*.pdf`, `ko/pdf/`. Note: `extract/` is **tracked** (not ignored) — the consolidated `.txt` parts are committed as provenance
- `filemode = false` in git config (cross-platform safe)

## Obsidian Setup

1. Open the cloned folder as an Obsidian vault
2. Community plugin **obsidian-git** is pre-configured but has auto-save/push/pull **disabled** (interval 0)
3. `tools/` and `ko/pdf/` are excluded from Obsidian file explorer via `userIgnoreFilters` in `.obsidian/app.json`

## AI Agent Rules

1. Always maintain the bilingual mirror — when adding/editing an article in one language, update the corresponding file in the other language
2. Filename convention: `{FirstAuthor}{Year}_{Journal}_{Keyword}.md` (e.g., `Anderson2016_Nature_SCI+Mouse+Astrocytes.md`). The `_{Keyword}` topic suffix is expected; join multiple terms with `+`. Journal uses a standard abbreviation (`NatComm`, `CellRep`, `eLife`, …)
3. When adding a new article, create both `en/articles/{stem}.md` and `ko/articles/{stem}.md` with the same structure; reviews go to `ko/reviews/{stem}.md` (ko only)
3a. Tag every note with its regeneration subject (`SpinalCord` or `Chondrocyte`) alongside the `YYYY-MM` extraction month, e.g. `tags: [2026-07, SpinalCord]`
3b. Whenever an agent creates or modifies a note, append one entry to the `log` frontmatter list: `"<YYYY-MM-DD> · <action> · <Model> (<Tool>)[ · <what changed>]"` (append at the end, never rewrite prior entries). This applies to content edits, renames, retags, and frontmatter changes — not to no-op reads.
4. Do not modify files under `tools/` — that is a separate submodule repository
5. Do not modify `.obsidian/workspace.json` (per-machine state, gitignored)
6. Keep section order consistent (original research): Title → Citation → Background → Key Experiment Methods → Results → Perspective
7. Set `extract_file` in frontmatter to the split extract part containing the paper, and make sure that part has a `===== <note-stem> =====` block for it
7a. Author notes from extracted text, not the PDF directly: run `tools/process_pdf.py` (or import its `extract_text()`) to produce the text FIRST, then use that text to verify the filename/DOI and write the note. Do not re-implement PDF extraction (PyMuPDF/`fitz` is the extractor; there is no local `pdftotext`)
8. After a note is written, move its PDF into `ko/pdf/done/` (reviews → `ko/pdf/done/review/`) renamed to the note stem
9. Papers outside the spinal-cord/regeneration scope (e.g. unrelated cancer/fibrosis, ion-channel biophysics, ossification, method-only tools) are left un-noted; their PDFs stay under `ko/pdf/` for separate review
10. Commit messages should follow the pattern: `{action}: {lang} {description}` (e.g., `add: en Wu2021_NatComm`, `edit: ko Haseeb2021_PNAS`)
