# Week 8 Focus Mode

A mobile-friendly personal productivity PWA for Week 8: Sunday 7 June 2026 to Saturday 13 June 2026.

## Features

- Sunday-first Egyptian work week layout
- MFVA study tracking
- Prayer and spiritual tracker
- Water tracker
- Tiny wins and mood/reflection
- LocalStorage persistence with `week8_` keys
- Today and full-week TXT export
- Installable PWA manifest
- Service worker caching and notification display support

## How to run

Open `index.html` directly, or serve the folder locally:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder.
3. Go to Settings → Pages.
4. Select the main branch and root folder.
5. Open the published GitHub Pages URL.

## Note on reminders

Browser reminders are scheduled while the app is open. Full background push reminders require a server push service, which is outside a static GitHub Pages app.
