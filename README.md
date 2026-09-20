# RESET 66

A mobile-first 66-day habit reset app.

## Run locally

```bash
npm install
npm run dev
```

Then open the local Vite URL.

## Build

```bash
npm run build
```

The production files are created in `dist/`.

## GitHub Pages / static hosting

This app is client-side only and stores data in browser localStorage. It does not require a database.

For GitHub Pages, a simple static deployment workflow can run `npm ci` and `npm run build`, then publish `dist/`.

## V1 features

- 66-day challenge engine
- Daily habit checklist
- Required habits
- Streak calculation
- 66-day calendar
- Habit performance
- Daily journal
- Local persistence
- Mobile-first dark UI
- PWA manifest

## V2 additions

- Achievement system
- Clickable historical 66-day calendar
- Rich habit creation with icon, accent and required controls
- Improved interaction states and mobile polish

## V3 additions

- Day completion celebration
- Weekly review
- Historical journal review from the 66-day calendar
- Achievement progression
- Stronger daily feedback
