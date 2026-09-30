# Claude Code Skills & Agents

Everything Claude Code can use on this setup, as of September 30, 2026. Run a skill by typing `/<skill-name>` in Claude Code, or just describe the task and Claude picks the right one.

## Custom skills (made for Mirella Manelli)

| Skill | What it does | How to use |
|---|---|---|
| `rough-cut` | Rough-cuts a talking video for Final Cut Pro. Removes dead air, long pauses, false starts, repeated takes and filler, then makes an FCPXML timeline to import into Final Cut. It can also export an MP4. | `/rough-cut <video path> [tight\|natural] [render]` |

**Rough-cut notes**
- Output goes to a `<video name>.roughcut/` folder next to the video.
- `tight` makes quick cuts for YouTube or social media. `natural` (the default) leaves slightly longer pauses.
- To import: Final Cut Pro → File → Import → XML… → pick the `.fcpxml` file.
- It needs ffmpeg (or `imageio-ffmpeg`) and `faster-whisper` (Python).

## Custom agents

| Agent | What it does |
|---|---|
| `mirella-manelli-ad-copy` | Writes Mirella Manelli ad copy: Facebook/Instagram, Google and display ads, landing pages, headlines and CTAs. It works with the paid ads strategist. |
| `paid-ads-strategist` | Strategy, planning, trend analysis and optimization for Facebook and Google Ads campaigns. |

## Documents & files

| Skill | What it does |
|---|---|
| `docs` | Editable docs you can share and comment on (reports, proposals, guides, SOPs, letters). They export to Word, PDF, Markdown or Google Docs. |
| `docx` | Creates, reads and edits Word documents (.docx / .dotx), including tracked changes and templates. |
| `pdf` | Reads, merges, splits, rotates, watermarks, fills in, encrypts and OCRs PDFs. |
| `pptx` | Creates, reads and edits PowerPoint decks (.pptx / .potx). |
| `xlsx` | Creates, cleans and edits spreadsheets (.xlsx, .csv, .tsv), including formulas and charts. |
| `google-workspace` | Creates and edits Google Docs, Sheets and Slides in Google Drive. |

## Design, pages & visuals

| Skill | What it does |
|---|---|
| `artifact-design` | Design guidance for Artifacts (hosted web pages on claude.ai). |
| `artifact-diagramming` | Clear diagrams inside Artifacts. |
| `artifact-capabilities` | Interactive Artifacts that save data, share state between viewers, or read live data. |
| `dataviz` | Charts, graphs, dashboards and KPI tiles with consistent, accessible colors. |

## Research & daily workflow

| Skill | What it does |
|---|---|
| `deep-research` | Multi-source research combined into a full written report. |
| `morning` | Builds your morning brief, or sets it up as a weekday routine. |
| `schedule` | Schedules cloud agents to run on a set schedule, or once at a set time. |
| `loop` | Repeats a prompt or command on an interval (e.g. `/loop 5m /foo`). |
| `import-memory` | Imports a memory export from another AI assistant into Claude's memory. |

## Computer & browser control

| Skill | What it does |
|---|---|
| `computer-use` | Controls desktop apps (Finder, Notes, Final Cut, etc.) through the Claude desktop app. Computer use must be turned on first. |
| `chrome-browser` / `claude-in-chrome` | Automates your real Chrome browser: clicking, filling forms, screenshots, console logs. |
| `built-in-browser` | Uses the browser built into the Claude desktop app. |

## Coding & Claude Code setup

| Skill | What it does |
|---|---|
| `code-review` | Reviews code changes or a pull request for bugs. |
| `simplify` | Cleans up changed code (reuse, simplification, efficiency). |
| `security-review` | Reviews pending code changes for security issues. |
| `run` | Launches and drives a project's app to check that a change works. |
| `init` | Creates a `CLAUDE.md` file that documents a codebase. |
| `claude-api` | Reference for building with the Claude API / Anthropic SDK. |
| `skill-creator` | Creates, edits and tests new skills. |
| `update-config` | Changes Claude Code settings: permissions, env vars, hooks and automations. |
| `keybindings-help` | Customizes Claude Code keyboard shortcuts. |
| `fewer-permission-prompts` | Adds safe, common commands to an allowlist so you get asked less often. |

## Connected apps

These connected apps are available alongside the skills:

- **Google Drive**: search, read, create, copy, share and update files.
- **Claude Docs**: create and edit living docs.
- **Gmail** and **Google Calendar**: available after you sign in to them.
