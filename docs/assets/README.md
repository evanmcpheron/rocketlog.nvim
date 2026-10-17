# Media guide

This directory contains the screenshots and GIFs embedded in the project documentation.

The GIFs show real RocketLog workflows in an isolated Neovim session. Key captions use Space as `<leader>`; the dashboard comment demo includes the confirmation for the file-wide action.

## Included media

| File                           | Type       | Used in                          | What it shows                                                    |
| ------------------------------ | ---------- | -------------------------------- | ---------------------------------------------------------------- |
| `hero-overview.gif`            | GIF        | `README.md`                      | Open a file, insert a log, save, open dashboard, open help modal |
| `dashboard-overview.png`       | Screenshot | `README.md`                      | Entire dashboard with header, list, footer, preview              |
| `dashboard-help-modal.png`     | Screenshot | `README.md`, `docs/DASHBOARD.md` | The help modal open over the dashboard                           |
| `first-log.png`                | Screenshot | `docs/GETTING_STARTED.md`        | Simple TS file with one inserted RocketLog                       |
| `getting-started.gif`          | GIF        | `docs/GETTING_STARTED.md`        | First-run workflow from insert to dashboard help                 |
| `motion-logging.gif`           | GIF        | `docs/USAGE.md`                  | Motion-based insertion examples                                  |
| `stale-entry.png`              | Screenshot | `docs/USAGE.md`                  | Dashboard entry marked stale                                     |
| `dashboard-anatomy.png`        | Screenshot | `docs/DASHBOARD.md`              | Annotated or clearly framed dashboard panes                      |
| `dashboard-comment-toggle.gif` | GIF        | `docs/DASHBOARD.md`              | Toggle one log with `c`, then use `C` and confirm with `y`       |

---

## Capture tips

### General

- use a clean colorscheme with strong contrast
- keep the font readable
- crop tightly around the relevant UI
- avoid giant empty margins
- hide unrelated plugins if they clutter the shot

### GIFs

- keep them short, around 6–12 seconds
- do one workflow per GIF
- make sure key presses are clear from the resulting UI changes

### Screenshots

- prefer real plugin output over mockups
- include enough surrounding code to give context
- for dashboard shots, include at least:
  - one file group,
  - one selected log,
  - preview pane content,
  - footer cheatsheet content.

---

Use relative paths like:

```md
![RocketLog dashboard overview](./docs/assets/dashboard-overview.png)
```

or from inside docs:

```md
![RocketLog getting started](./assets/getting-started.gif)
```
