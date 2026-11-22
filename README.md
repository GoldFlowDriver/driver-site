# GOLD FLOW driver: download page

The public install / update page of the GOLD FLOW driver app: `index.html`, `version.json` (what phones check for updates), `vercel.json` and the signed APK.
Only these files live here. The app source is in a private repository.

New version: replace `gold-flow-driver.apk`, update `versionCode`, `versionName` and `sha256` in `version.json`, and the file name in `vercel.json` (Content-Disposition).
Vercel: Framework Other, no build command, root = repository root.
