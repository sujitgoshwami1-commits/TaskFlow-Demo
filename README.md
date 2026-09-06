# TaskFlow — Project & Task Management with Kanban Board

A single-file, offline-friendly project and task management system with a drag-and-drop Kanban board — built for teams managing internal work and client projects side by side.

**[View Live Demo →](#)** *(replace with your GitHub Pages demo link)*

---

## Features

- **Kanban Board** — drag and drop tasks between To Do, In Progress, Review, and Done columns
- **Projects** — organize tasks by project, and link projects to clients where relevant
- **Team Management** — assign tasks to team members and see each person's current workload
- **Clients** — track which projects belong to which client
- **Priority & Due Dates** — Urgent/High/Medium/Low priority tags, with overdue tasks flagged automatically
- **Filters** — filter the board by project or assignee, and search across tasks
- **Reports Dashboard** — completion rate, tasks per project, tasks by column, tasks by assignee
- **Day / Night theme** — toggle between light and dark mode
- **No backend required** — runs entirely in the browser using LocalStorage; no server, database, or account needed
- **Responsive** — works on desktop, tablet, and mobile

## Getting Started

1. Download or clone this repository
2. Open `index.html` in any modern browser
3. That's it — demo data loads automatically on first run

No build step, no dependencies, no installation.

## Tech Stack

- HTML5, CSS3 (custom properties for theming), vanilla JavaScript
- Native HTML5 Drag and Drop API for the Kanban board — no external libraries
- Browser LocalStorage for data persistence
- Google Fonts (Space Grotesk, Inter, JetBrains Mono)

## Data & Privacy

All data is stored locally in your browser's LocalStorage. Nothing is sent to any server. Clearing your browser data will reset the app; use the **Reset Demo Data** button in the sidebar to restore the sample dataset at any time.

## Important

This is a front-end, browser-based application. It does not include a hosted backend, cloud database, user authentication, or real-time sync across devices or team members.

Your data persists in the browser until you clear site data or use the Reset Demo Data button — it does **not** auto-reset on its own, so it's safe for real day-to-day use. (The separately hosted live demo does reset nightly, so visitors always see a clean sample dataset — that behavior is not present in this package.)

## License

See `LICENSE` file.

## Support

Built and maintained by UpComing Solution. For customization, bulk licensing, or a hosted/multi-user version with a real backend, get in touch.
