# kb-SpinalCord

An LLM Wiki Obsidian vault for **spinal cord** research literature.

## Structure

```
.
├── en/        # English notes
│   └── articles/
├── ko/        # Korean notes
│   └── articles/
└── tools/     # Shared utilities (git submodule)
    └── git@github.com:taejoonlab/kb-tools.git
```

## Languages

The vault operates in two languages:
- **ko/** — Korean notes for the spinal cord project
- **en/** — English translations mirroring the same structure

Each article note follows a consistent format: Citation, Background, Key Experiment Methods, Results, Perspective.

## Setup

1. Clone with submodules:
   ```bash
   git clone --recurse-submodules git@github.com:taejoonlab/kb-SpinalCord.git
   ```

2. Open the folder as an Obsidian vault.

3. (Optional) Enable the Obsidian Git plugin for auto-commit and sync.

## Tools

The `tools/` directory is managed as a separate submodule repository. It is excluded from the Obsidian file explorer via `userIgnoreFilters` in `.obsidian/app.json`, but remains under git version control.
