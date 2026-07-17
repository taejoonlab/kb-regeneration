# kb-SpinalCord — LLM Wiki Obsidian Vault

## Project Overview

Bilingual (en/ko) Obsidian vault for **spinal cord** research literature. Each article has structured notes in both languages under `en/articles/` and `ko/articles/`.

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
tags: [YYYY-MM]
extract: YYYY-MM-DD
extract_file: extract/YYYY-MM-DD_pNN.txt
---
```
- `extract_file` points to the split extract part that holds this paper's source text;
  find the block inside that file by the anchor `===== <note-stem> =====`.

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

## Extracted text & PDF organization

- **`extract/`** (git-tracked): source PDF text consolidated per extraction date, split into
  ~2 MB parts `extract/YYYY-MM-DD_pNN.txt`. Each paper is one block delimited by
  `===== <note-stem> =====`. This is the provenance record for the notes.
- **`ko/pdf/`** (gitignored working dir): raw PDFs. Once a note is written, the PDF is moved to
  `ko/pdf/done/` (review PDFs to `ko/pdf/done/review/`), renamed to match its note stem.
  PDFs left directly under `ko/pdf/` are not yet noted (off-topic or to-review).
- `ko/pdf/notes/` holds per-file working artifacts (`*_extracted.txt`, `00_triage.md`,
  `0N_*_log.txt`) — gitignored; the committed `extract/` parts supersede the per-file extracts.

## Git Conventions

- Clone with submodules: `git clone --recurse-submodules git@github.com:taejoonlab/kb-SpinalCord.git`
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
4. Do not modify files under `tools/` — that is a separate submodule repository
5. Do not modify `.obsidian/workspace.json` (per-machine state, gitignored)
6. Keep section order consistent (original research): Title → Citation → Background → Key Experiment Methods → Results → Perspective
7. Set `extract_file` in frontmatter to the split extract part containing the paper, and make sure that part has a `===== <note-stem> =====` block for it
8. After a note is written, move its PDF into `ko/pdf/done/` (reviews → `ko/pdf/done/review/`) renamed to the note stem
9. Papers outside the spinal-cord/regeneration scope (e.g. unrelated cancer/fibrosis, ion-channel biophysics, ossification, method-only tools) are left un-noted; their PDFs stay under `ko/pdf/` for separate review
10. Commit messages should follow the pattern: `{action}: {lang} {description}` (e.g., `add: en Wu2021_NatComm`, `edit: ko Haseeb2021_PNAS`)
