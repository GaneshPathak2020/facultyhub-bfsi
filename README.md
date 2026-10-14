# FacultyHub BFSI — Professor Productivity Dashboard

A self-contained, browser-based demo dashboard for an FDP session with faculty teaching MBA/PGDM Banking, Finance and Insurance.

## Run locally

1. Download and extract `FacultyHub_BFSI_Local_GitHub.zip`.
2. For a quick preview, open `index.html` in Chrome, Edge, Firefox, or another modern browser.
3. For the most consistent browser-storage behaviour, open a terminal in this folder and run `py -m http.server 8000` on Windows (or `python -m http.server 8000` on macOS/Linux), then visit `http://localhost:8000`. Stop the server with Ctrl+C when finished.
4. Use the sidebar to explore the dashboard. Edits are saved in that browser profile using `localStorage`.

The app has no external dependencies, API key, paid subscription, database, or internet requirement for its core features.

## Host on GitHub Pages

1. Sign in to GitHub and create a new repository (for example `facultyhub-bfsi`).
2. Upload `index.html` and `README.md` from this package directly to the repository root (not inside an extra subfolder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then save.
5. Wait for GitHub Pages to publish the static site; use the URL shown in Settings → Pages.

You can also rename `index.html` only if you change the entry path accordingly; normally leave its name as `index.html`.

## Important demo limitations

- All seeded faculty names, student records, attendance figures, submissions, and leaderboard metrics are fictional.
- The AI Assistant uses prepared examples only; no model API is connected.
- The calendar is local only; there is no Google/Outlook sync, notifications service, sign-in, or institutional system integration.
- Edits are stored in the current browser profile via localStorage and do not sync between different devices or users.
- Do not enter personal, confidential, student, or real banking/insurance customer data.
- This is an FDP prototype, not a production student information system. Production use would require institutional review, security controls, authentication and authorisation, backups, accessibility and privacy assessments, and a secure data backend.

## Features in this prototype

- Overview and summary cards
- Task list with priority/status filters and task creation/completion
- Calendar and meetings with event creation
- Teaching plan with add/edit/remove lecture
- Fictional student roster with search and sample student records
- Assignments and a mock rubric evaluation workflow
- Demo-only faculty workflow leaderboard
- Offline mock AI assistant prompt library
- CSV export for tasks, students, assignments, and calendar events
- Restore sample data and privacy notice
