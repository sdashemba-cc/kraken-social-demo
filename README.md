# Kraken Social Prototype (v3)

A clickable demo of proposed Kraken social features. All names, prices and counts are made up. Nothing places a real order.

Live link after setup: https://sdashemba-cc.github.io/kraken-social-demo/

## Update an existing repo (you already did the first setup)

1. Unzip this folder.
2. Open your `kraken-social-demo` repo on GitHub. Click Add file, then Upload files.
3. Drag in everything from this folder (`index.html`, `sw.js`, `manifest.webmanifest`, `.nojekyll`, and the `icons` folder). GitHub replaces files with the same names. Commit to main.
4. Wait about a minute for Pages to redeploy, then reload the link. If you still see the old version, hard refresh (Ctrl/Cmd+Shift+R), or close and reopen the installed app once.

Only `index.html` and `sw.js` changed from v2. The icons and manifest are identical, so you can upload just those two files if you prefer.

## First-time setup

1. On GitHub, click New repository. Name it `kraken-social-demo`, set it to Public (free GitHub Pages needs a public repo), and create it.
2. Click "uploading an existing file" on the new repo page. Drag in everything from this folder and commit to main.
3. Go to Settings, then Pages. Under Build and deployment, choose Deploy from a branch, pick `main` and `/ (root)`, and Save.
4. Wait about a minute, then open the link above.

## Install it on a phone

- iPhone: open the link in Safari, tap Share, then Add to Home Screen.
- Android: open the link in Chrome, tap the menu, then Install app.

## Notes

- The icon is a placeholder, not Kraken's logo.
- It loads fonts from Google Fonts, so the first open needs a connection. After that it works offline.
- The service worker cache name is now `kraken-social-v3`, and the service worker now asks the server for fresh files on every load, so future updates show up on the next reload without clearing site data.
