# RESET 66

**66 DAYS. ONE RESET.**

A mobile-first 66-day habit reset app built with React and Vite.

## Included

- 66-day reset engine
- Daily habit checklist
- Required-habit completion
- Streak tracking
- 66-day progress calendar
- Habit performance statistics
- Achievements
- Daily journal with mood and energy tracking
- Weekly review
- Add/remove/customise habits
- Restart/reset function
- Local browser storage — no account or backend required
- Responsive mobile/desktop interface
- GitHub Pages deployment workflow

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## GitHub Pages

This package includes `.github/workflows/deploy.yml`.

1. Upload the contents of this package to the **root of your GitHub repository**.
2. In GitHub open **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push/commit to the `main` branch, or manually run **Deploy RESET 66** from Actions.
5. For the `phillipdevilliers19-cell/test3` repository the site is:
   `https://phillipdevilliers19-cell.github.io/test3/`

The Vite configuration uses a relative base so the build works from a repository sub-path.

## Data

Your habits, completions and journal entries are stored in `localStorage` on the device/browser. Clearing browser site data will clear the app data.
