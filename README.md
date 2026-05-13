# Student Success Hub (Smart Study Assistant)

A simple, single-page web application to help students stay organized and focused.

## Features
- **Study Planner**: add/edit/delete study tasks with category, priority, and optional deadline
- **Budget Tracker**: track income/expenses and see your balance
- **Weekly Goals**: add goals, mark them complete, and view progress
- **Reflection Journal**: save reflection entries with timestamps
- **Theme toggle**: light/dark mode (persisted in your browser)
- **Offline-friendly**: uses `localStorage` to keep your data in the browser

## How to run locally
This project is static.

1. Open `index.html` in your browser.
   - Double-click `index.html`, or
   - Right-click → “Open with …”

### Recommended (optional) static server
If your browser enforces stricter rules for local files, you can serve it:

- Python 3:
  - `python -m http.server 5500`

Then open: `http://localhost:5500`

## Data storage
All user data is stored in your browser via **`localStorage`**:
- tasks
- expenses
- goals
- reflections
- budget totals
- theme preference

## License
See [LICENSE](LICENSE).

