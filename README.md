# Smart Priority Quadrant

A single-file, zero-dependency priority matrix that plots your tasks by **urgency** and **importance** — inspired by the Eisenhower Matrix.

**[Live Demo →](https://ankitagarwal9.github.io/smart-priority-quadrant/)**

![Smart Priority Quadrant](https://img.shields.io/badge/version-3.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)

---

## Features

- **Visual quadrant** — tasks plotted automatically by deadline proximity (X axis) and importance you set (Y axis)
- **Auto-positioning** — urgency updates in real time as deadlines approach
- **Three views** — Quadrant chart, Task List, Archive
- **Recurring tasks** — daily/weekly with multiple time slots, expiry banners
- **Colour-coded quadrants** — Do Now, Schedule, Defer, Delegate
- **localStorage persistence** — tasks save automatically in your browser, no account needed
- **Zero setup** — open the file and start adding tasks

## How to Use

### Option 1: Live (no install)
Open **[ankitagarwal9.github.io/smart-priority-quadrant](https://ankitagarwal9.github.io/smart-priority-quadrant/)** in any browser.

### Option 2: Local
```bash
git clone https://github.com/ankitagarwal9/smart-priority-quadrant.git
# Open index.html in your browser
open index.html
```

No build step. No server. No dependencies.

## Data & Privacy

All tasks are stored in **your browser's localStorage** only. Nothing is sent to any server. Each device/browser has its own separate task list.

## The Quadrant

|  | **Urgent** | **Not Urgent** |
|---|---|---|
| **Important** | Do Now | Schedule |
| **Not Important** | Delegate | Defer |

Urgency is calculated automatically from your deadline. Importance is set manually (0–100 slider).

## License

MIT — free to use, modify, and share.
