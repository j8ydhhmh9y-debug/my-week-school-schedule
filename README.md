# My Week

A lightweight Year 7 school schedule that works as a static website and installable web app.

## Run locally

Open `index.html` directly, or serve the folder with any static web server.

## Views

- Student view: `/`
- Read-only teacher view: `/?view=teacher`

The teacher view hides personal reminders and editing controls.

## GitHub Pages

1. Push these files to the repository's default branch.
2. Open **Settings → Pages** in GitHub.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the default branch and `/ (root)`, then save.

## Data and privacy

Schedule edits currently use browser `localStorage`. They sync neither across devices nor to another person opening the teacher link. Shared synchronization will require an authenticated cloud database. Email, Google Classroom, and homework integrations are intentionally not enabled yet.
