# Disney Pin Tracker

Installable iPhone-friendly web app for Disney pin collecting.

## Current contents
- Hidden Disney 2025 Wave A — Disneyland Resort
- Placeholder collection slots for Wave B, Wave C, Wave D, and custom pins

## Features
- Owned / ISO / Trader status
- Quantity tracking
- Notes for purchase/trade source and condition
- Overall and per-set progress
- Search by pin, set, character/tag, chaser, or ID
- Backup/restore JSON
- Offline-capable PWA after first load
- Light/dark theme
- Future-proof data model so app updates should not wipe user progress

## Publish with GitHub Pages
1. Open this project folder on a PC.
2. Upload all files and folders to the root of your GitHub repository:
   - `index.html`
   - `manifest.webmanifest`
   - `service-worker.js`
   - `data/`
   - `icons/`
   - `images/`
   - `README.md`
3. In GitHub: Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: main. Folder: `/ root`.
6. Save.
7. Open the GitHub Pages URL in Safari on iPhone.
8. Tap Share → Add to Home Screen.

## Updating future waves
Add new pins to `data/pins.json` and add/update collection info in `data/collections.json`. Keep the same `collectionId` and pin `id` values once published so saved user data stays linked.
