# JD Finance — Mobile-Optimized PWA

## GitHub Pages setup
1. Create a GitHub repository named `jd-finance`.
2. Upload **all files and folders in this directory** (do not upload the ZIP itself).
3. In GitHub: Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: `main`, folder: `/ (root)`.
6. Save and wait for the Pages URL.
7. Open the URL in Chrome on Android → menu ⋮ → **Add to Home screen** / **Install app**. The mobile layout includes a slide-out left drawer and a fixed bottom navigation bar.

## Important data note
JD Finance stores its current data in the browser's local storage. The PWA cache allows the app shell to work offline, but it does NOT replace backups. Use Settings → Download backup regularly and store the JSON backup in Google Drive.

## GitHub upload structure
jd-finance/
- index.html
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png
- README.md

## Next production step
For business-critical data, add SQLite/IndexedDB and encrypted Google Drive/cloud backup before relying on the app as the only copy of your records.
