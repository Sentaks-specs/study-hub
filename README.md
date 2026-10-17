# Sen's Study Hub: make it an app

Files in this folder (keep them together):
- index.html: the whole study hub (all subjects are inside it)
- manifest.json: tells the phone this is an installable app (name, icon, colors, no browser bars)
- sw.js: lets it open offline after the first visit
- icon-*.png and apple-touch-icon.png: the app icons

## 1. Put it online (free, GitHub Pages)
1. Sign in at github.com and click New repository. Name it study-hub and make it Public.
2. Click "uploading an existing file" and drag in ALL files from this folder (not the folder itself). Commit.
3. Go to Settings, then Pages. Under "Build and deployment", set Source to "Deploy from a branch", Branch "main", folder "/ (root)", then Save.
4. Wait 1 to 2 minutes. Your link will be https://YOUR-USERNAME.github.io/study-hub/

## 2. Install it on your phone
- Android (Chrome): open your link, tap the three dots, then "Install app" (or "Add to Home screen"). It opens full screen with no address bar.
- iPhone (Safari): open your link, tap Share, then "Add to Home Screen".

## 3. Updating later
Replace index.html on GitHub, and change CACHE in sw.js from "studyhub-v1" to "studyhub-v2" so phones pick up the new version.

## Optional: a real APK
Go to pwabuilder.com, paste your GitHub Pages link, and choose Android to get an APK you can install.
