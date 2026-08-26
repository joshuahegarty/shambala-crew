# Shambala 2026 Crew Companion

A single-page festival app (PWA) for the crew. Installs to the home screen and works offline.

## Put it online with GitHub Pages
1. Create a new repository, e.g. `shambala-crew`.
2. Upload **all** files from this folder to the repo root: index.html, manifest.webmanifest, service-worker.js, icon-180.png, icon-192.png, icon-512.png.
   - Web UI: repo > **Add file** > **Upload files** > drag them in > **Commit**.
   - Or CLI: `git add . && git commit -m "app" && git push`.
3. Repo **Settings > Pages** > Source: **Deploy from a branch** > Branch **main** / **/(root)** > **Save**.
4. Wait ~1 min. Your link shows at the top of the Pages settings, like `https://YOURNAME.github.io/shambala-crew/`.
5. Share that link. On a phone open it, then **Share > Add to Home Screen** (iPhone) or **menu > Add to Home screen** (Android).

## Notes
- Each person's picks/photos/moments stay on their own phone. Use the **Crew** tab to swap codes and see overlaps.
- Spotify players and the camera need internet / a real page.
- To update later: replace the files, re-commit. If an old version sticks, bump `shambala-crew-v1` in service-worker.js to force a refresh.
