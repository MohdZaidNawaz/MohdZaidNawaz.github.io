# Walkie site

Static files for Walkie invite links (GitHub Pages). Contains no secrets:
- `.well-known/assetlinks.json` lets Android open `https://<this host>/invite/<code>` straight in the Walkie app.
- `404.html` / `invite/index.html`: fallback page when the app is not installed (open the app, or install it).
