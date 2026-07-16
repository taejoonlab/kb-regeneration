# kb-SpinalCord — LLM Wiki Obsidian Vault

## Project Overview

Bilingual (en/ko) Obsidian vault for **spinal cord** research literature. Each article has structured notes in both languages under `en/articles/` and `ko/articles/`.

## Repository Structure

```
.
├── en/articles/   # English article notes
├── ko/articles/   # Korean article notes (same filenames as en/)
├── tools/         # Git submodule (git@github.com:taejoonlab/kb-tools.git)
└── .obsidian/     # Obsidian config (tracked, except workspace.json)
```

## Note Format

Every article note follows these sections in order:
1. `# Title` — full article title
2. `## Citation (NLM)` — NLM-formatted citation + DOI link
3. `## Background` — research background
4. `## Key Experiment Methods` — numbered methods
5. `## Results` — key findings
6. `## Perspective` — significance & future directions

## Git Conventions

- Clone with submodules: `git clone --recurse-submodules git@github.com:taejoonlab/kb-SpinalCord.git`
- If already cloned without submodules: `git submodule update --init --recursive`
- Submodule URL uses **SSH** (`git@github.com:taejoonlab/kb-tools.git`) — ensure SSH key is configured
- `.gitignore` ignores: `.obsidian/workspace.json`, `.obsidian/cache/`, `.obsidian/plugins/obsidian-git/obsidian_askpass.sh`, `*.pdf`, `ko/pdf/`
- `filemode = false` in git config (cross-platform safe)

## Obsidian Setup

1. Open the cloned folder as an Obsidian vault
2. Community plugin **obsidian-git** is pre-configured but has auto-save/push/pull **disabled** (interval 0)
3. `tools/` and `ko/pdf/` are excluded from Obsidian file explorer via `userIgnoreFilters` in `.obsidian/app.json`

## AI Agent Rules

1. Always maintain the bilingual mirror — when adding/editing an article in one language, update the corresponding file in the other language
2. Filename convention: `FirstAuthorYYYY_Journal.md` (e.g., `Wu2021_NatComm.md`)
3. When adding a new article, create both `en/articles/FirstAuthorYYYY_Journal.md` and `ko/articles/FirstAuthorYYYY_Journal.md` with the same structure
4. Do not modify files under `tools/` — that is a separate submodule repository
5. Do not modify `.obsidian/workspace.json` (per-machine state, gitignored)
6. Keep section order consistent: Title → Citation → Background → Key Experiment Methods → Results → Perspective
7. Commit messages should follow the pattern: `{action}: {lang} {description}` (e.g., `add: en Wu2021_NatComm`, `edit: ko Haseeb2021_PNAS`)
