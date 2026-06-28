# Disney Pin Tracker v3

Polished installable iPhone-friendly Disney pin tracker.

## New in v3

- Automatic real image loading by pin ID
- Full-screen image viewer
- Polished card/grid layout
- Better progress by set and overall
- Trader mode, ISO mode, favorite mode
- Expanded pin details:
  - Quantity
  - Date acquired
  - Source
  - Price
  - Condition
  - Trade value
  - Notes
- Light/dark theme
- Backup/restore
- Offline-capable PWA
- Keeps the same local storage key as v2, so existing owned/ISO/trader data should persist

## Add real pin images

Upload your own photos into:

`images/pins/`

Name each file by Pin ID:

- `90912.jpg`
- `90913.jpg`
- `90968.jpg`

Supported extensions:

- `.jpg`
- `.jpeg`
- `.webp`
- `.png`

The app checks for images in this order:

1. `images/pins/90912.jpg`
2. `images/pins/90912.jpeg`
3. `images/pins/90912.webp`
4. `images/pins/90912.png`

If no image exists, it uses a placeholder.

## Update your GitHub Pages site

Upload/replace:

- `index.html`
- `manifest.webmanifest`
- `service-worker.js`
- `data/`
- `icons/`
- `images/`

Then wait a minute and refresh the app on your iPhone. If it does not update immediately, close the Home Screen app completely and reopen it, or open the GitHub Pages URL in Safari and refresh.
