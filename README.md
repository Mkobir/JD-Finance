# JD Finance — Mobile-Optimized PWA

This version is designed for real phone screens: no forced desktop width, responsive sizing, slide-out left menu, and a fixed bottom navigation bar.

## GitHub Pages
Upload all files to your existing `jd-finance` repository, replacing the old files. Keep the `icons` folder. Then wait for GitHub Pages to redeploy.

If an already-installed PWA still shows the old layout, fully close it and refresh the site once. If necessary, remove the installed shortcut and install it again so the new service-worker cache is used.

## Data
Business data remains in localStorage under the same key `jd_finance_v1`, so replacing the app files does not intentionally erase existing data. Still make a JSON backup before updating.
