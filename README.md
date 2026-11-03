# DSA in C++ — Android App

This is a lightweight Progressive Web App (PWA) version of your DSA checklist.

## Put it online (one-time setup)
A PWA needs an HTTPS address to install. The easiest free method is GitHub Pages.

1. Extract this ZIP.
2. Create a new GitHub repository, for example `dsa-checklist`.
3. Upload **the contents of this folder** (not the enclosing folder) to the repository's main branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then Save.
7. Wait for GitHub Pages to publish. Your app URL will look like:
   `https://YOUR-USERNAME.github.io/dsa-checklist/`

## Install on Android
1. Open that URL in **Chrome** on your Android phone.
2. Tap Chrome's **⋮** menu.
3. Choose **Install app** (or **Add to Home screen**, depending on Chrome version).
4. Confirm. The DSA Checklist icon will appear on your home screen.

After opening the app once while online, it can load offline. Your checkbox progress is saved in that browser/app storage. Avoid clearing Chrome/site data if you want to preserve progress.

## Important
- Do not open `index.html` directly from the phone's file manager if you want install/offline features. Use the HTTPS GitHub Pages URL.
- Keep `index.html`, `manifest.webmanifest`, `service-worker.js`, and the `icons` folder together at the repository root.
