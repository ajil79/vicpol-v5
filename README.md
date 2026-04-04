# VicPol Tool v5

Victoria Police paperwork tool — single-file offline-capable web app.

## Features

- Arrest reports, warrants, bail conditions, field contacts, search & seizure, vehicle inspection
- OCR intake (Tesseract.js) — paste, drag & drop, or camera capture
- Traffic history analyser (demerit points, impound schedule)
- Per-section copy, editable preview
- Draft autosave, preset templates, signature pool
- Light/dark mode, mobile-optimised

## Deploy

### Vercel (recommended)

1. Push this repo to GitHub
2. Import the repo at [vercel.com/new](https://vercel.com/new)
3. No build settings needed — Vercel detects the static config automatically
4. Deploy

### Manual / local

Just open `index.html` directly in any modern browser. No server or build step required.

## Notes

- All data stays in the browser (`localStorage`) — nothing is sent to any server
- OCR loads Tesseract.js from jsDelivr CDN on demand — works offline once cached
- Tested on Chrome, Firefox, Safari, iOS Safari, Android Chrome
