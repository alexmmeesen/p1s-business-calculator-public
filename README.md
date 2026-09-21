# P1S Business Calculator Pro — APK Ready

This package is configured as a Progressive Web App (PWA) for Android packaging.

## Included
- `index.html` — calculator app
- `manifest.webmanifest` — PWA/Android manifest with required icons
- `sw.js` — offline service worker
- `icons/icon-192.png` — required 192x192 icon
- `icons/icon-512.png` — required 512x512 icon
- `icons/icon-512-maskable.png` — Android maskable icon
- `icons/icon-1024.png` — high-resolution icon

## Hosting
Host the folder on an HTTPS URL (GitHub Pages is suitable).

## PWABuilder
Enter the HTTPS PWA URL into PWABuilder and run the Android package workflow.

## Notes
- The app stores calculator data locally in the browser/device using localStorage.
- Monthly fixed overhead is allocated per order using expected monthly orders.
- No external JavaScript or CSS CDN is required.
