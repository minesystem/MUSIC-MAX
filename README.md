# NØV3X MUSIC MAX

A mobile-first personal music player website.

## Files
- `index.html` — app structure
- `style.css` — visual design
- `app.js` — player, playlists, favorites, queue, and imported audio
- `manifest.json` — installable web app details
- `service-worker.js` — caches the app shell for offline opening
- `icons/icon.svg` — app icon

## Publish with GitHub Pages
1. Upload every file and the `icons` folder to the root of your repository.
2. In GitHub, open Settings → Pages.
3. Choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. Open the published HTTPS website in Chrome on Android.
5. Use Chrome's menu → Install app or Add to Home screen if offered.

## Music and offline notes
- The included SoundHelix tracks are demonstration audio, not a bundled commercial music catalog.
- Use **Add music** to import audio files you own or are allowed to use.
- Imported files are stored in browser IndexedDB on that device. Browser storage can be cleared by the user or system, so keep your original files backed up.
- The service worker caches the app files, not online music catalogs or remote streaming audio. Streaming services need internet.
- Imported files are not automatically synced to other devices.
