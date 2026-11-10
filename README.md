# PokéSniper PWA — iPhone-only setup

This is a free, installable web-app starter. It is not an automated Target checkout bot and does not query Target. It stores your product list locally on the iPhone and lets you open Target listings to verify availability yourself.

## Publish free using only your iPhone

1. Open Safari and sign in or create an account at https://github.com.
2. Tap **+** → **New repository**. Name it `pokesniper`, set it to **Public**, and create it.
3. In the repository, choose **Add file** → **Upload files**.
4. Upload all files in this folder (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`). If the iPhone file picker is showing the extracted folder, use Select and choose all five files.
5. Commit the upload.
6. Open repository **Settings** → **Pages**.
7. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then **Save**.
8. Wait for GitHub Pages to publish. Your app URL will be `https://YOUR-USERNAME.github.io/pokesniper/`.

## Add it to your iPhone Home Screen

1. Open the published URL in Safari (not an in-app browser).
2. Tap the Share icon.
3. Choose **Add to Home Screen** and tap **Add**.
4. Launch PokéSniper from the new Home Screen icon.

## What works
- Add and remove Target product URLs.
- Keep a local watchlist on this iPhone.
- Manually mark a product in stock or unavailable.
- Open the product listing at Target.
- A basic browser notification may be available when you manually mark an item in stock, depending on iOS version and whether the site is installed to the Home Screen.

## What does not work yet
- Automatic Target stock checks.
- Reliable push notifications while the app is closed.
- Automatic checkout or purchase submission.

A genuine background monitor needs a cloud backend and a permitted inventory source. Any checkout should respect Target's terms, purchase limits, CAPTCHA, and user confirmation. Never put your Target password or payment details into this project.

## Privacy
The watchlist is stored in this browser's local storage. It is not sent to a server by this starter. Clearing Safari website data may erase the watchlist.
