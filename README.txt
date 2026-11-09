WRLDD VAULT — INSTALLABLE WEB APP PACKAGE

Files:
- index.html: app
- manifest.webmanifest: install identity and display settings
- sw.js: offline shell and viewed-image caching
- icon-192.png / icon-512.png: app icons

HOW TO HOST:
1. Upload ALL five files to the ROOT of your GitHub repository.
2. In the repository, open Settings > Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Select branch main and folder /(root), then Save.
5. Wait for GitHub Pages to publish. Open the published https://...github.io/... address in Chrome.
6. In Chrome, use the menu > Add to Home screen / Install app.

NOTES:
- This is a web app package, not an APK.
- Offline shell caching begins after the first successful online visit.
- Album cover image links may not load; this prototype uses placeholder external image endpoints and requires internet for covers. For offline album art, use artwork you have permission to store locally.
- User-added images are stored in this browser on this device. Clearing site data can erase them.
- The Owner PIN is a basic local screen, not secure authentication.
- This is an unofficial fan project, not affiliated with Juice WRLD's estate or label.
