# MYCARE.COM — Android PWA package

## Included
- `index.html` — your MYCARE website
- `manifest.webmanifest` — installable app details
- `service-worker.js` — offline app-shell cache
- `icons/` — app icons

## Free installation using GitHub Pages
1. Create/sign in to a GitHub account.
2. Create a new **Public** repository, for example `mycare-app`.
3. Upload every file and folder from this package (keep the folder structure).
4. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the HTTPS website.
6. Open the published link in Chrome on your Android phone.
7. Sign in / create your MYCARE account, then use the **Install MYCARE** button if shown.
   If the button is not shown, Chrome menu (⋮) → **Install app** or **Add to Home screen**.

## Important limitations of this current prototype
- It stores account data, notes, medicines and reminders in the browser's local storage on this device. It is not cloud-synced between phones.
- This PWA caches the app shell for offline opening after the first successful online visit. Some browser features may still need internet.
- Reminders are checked while the app/page is running. Android may pause background tabs, so do not rely on this prototype as a guaranteed alarm or medical alert.
- This is not a secure production account system: user records and role logic are browser-side. Do not store sensitive medical details or real patient records until a secure backend is added.
- Keep the app's published HTTPS URL the same after installation so updates can be received.
