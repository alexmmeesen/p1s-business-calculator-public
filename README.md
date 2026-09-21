# P1S Business Calculator Pro — APK-ready build

This package is the Android/PWA build foundation for the P1S Business Calculator Pro.

## Included
- Mobile-first calculator app
- Monthly fixed-overhead allocation
- PWA manifest
- Offline service worker
- Android-ready icons
- PWA shortcuts
- No external CDN dependencies required by the app shell

## Android packaging path
1. Publish this folder to an HTTPS website (GitHub Pages is a simple option).
2. Open the deployed URL in PWABuilder.
3. Validate the PWA and generate the Android package.
4. For a store release, complete Android signing and Play Console setup.

PWABuilder can generate store-uploadable packages and sideloadable packages for testing.

## Important
The final Android package needs a real HTTPS origin for the web app. We have not hard-coded a domain yet because the final hosting URL has not been chosen.

Once the hosted URL exists, the next Android-specific step is configuring the Trusted Web Activity package and Digital Asset Links for the chosen domain.

## Version
APK-ready foundation: v2.0.0
