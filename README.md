# RESET 66 — Arcade Edition

A mobile-first 66-day habit game built with React + Vite.

## Included
- Game-style 66-day journey map, XP, levels, streaks, checkpoints and achievements
- Habit groups with unlimited sub-missions
- Per-mission target, time and reminder settings
- Local-first progress storage with automatic migration from the previous RESET 66 data model
- PWA manifest
- Browser notifications when permission is granted and RESET 66 is active
- GitHub Pages deployment workflow

## Important notification note
The UI includes reminder scheduling and browser notifications. Reliable push delivery while the app is completely closed requires a cloud push service/server; this package intentionally does not invent credentials for one.

## GitHub Pages
Set Pages source to **GitHub Actions**. Push to `main` and the included workflow builds and deploys the Vite app.
