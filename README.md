# Todo List (Single-File Web App)

A lightweight, browser-based todo app built in a single `index.html` file with vanilla HTML, CSS, and JavaScript.

## Project Overview

This project is a no-build, single-page todo application focused on simplicity and usability. It lets you create, update, and manage tasks directly in the browser, with data persisted locally via `localStorage`.

The app includes:

- Task creation with title, optional due date, and optional description
- Task statuses: **Backlog**, **In progress**, and **Done**
- Inline status updates and task removal
- Edit modal for updating task details
- Overdue due-date highlighting for unfinished tasks
- Light/dark theme toggle with saved preference
- Keyboard and accessibility considerations (focus handling, Escape to close modal, ARIA labels)

## Tech Stack

- **HTML** for structure
- **CSS** for styling and theming
- **Vanilla JavaScript** for application logic and persistence
- **Browser `localStorage`** for saved tasks and theme preference

## Getting Started

Because this is a static single-file app, there is no installation step.

1. Open `index.html` directly in your browser, or
2. Serve the folder with any static server (optional)

Example:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Data Persistence

- Todos are stored under the key `simple-todos-v1`
- Theme preference is stored under the key `todo-list-theme`

All data stays in your browser (client-side only).

## File Structure

```text
.
├── index.html   # Entire app (markup, styles, and script)
└── README.md
```

