# NØV3X MUSIC MAX — Updated Project

A mobile-first personal music player web app for GitHub Pages.

## Project files
- `index.html` — app layout and controls
- `style.css` — responsive purple/neon styling
- `app.js` — music player, search, genres, favorites, playlists, queue, and audio import
- `manifest.json` — installable web app metadata and icons
- `service-worker.js` — caches the app shell for offline opening
- `icons/icon.svg` — scalable app icon
- `icons/icon-192.png` — Android/PWA icon
- `icons/icon-512.png` — high-resolution PWA icon

## Publish on GitHub Pages (phone-friendly)
1. Extract this ZIP on your phone.
2. Open your GitHub repository.
3. Upload the root files and the complete `icons` folder. Keep the folder structure exactly as shown.
4. Commit the upload to your `main` branch.
5. In Settings → Pages, select Deploy from a branch, `main`, and `/(root)`.
6. Open the published HTTPS address in Chrome.

## Install on Android
Open the published website in Chrome. Use the browser menu and choose **Install app** or **Add to Home screen** when available.

## Music and storage notes
- Demo audio is provided for testing the player. The demo tracks are not a commercial music library and their genre labels are only sample categories.
- Use **Add music** to import audio files you own or are allowed to use.
- Imported files are stored in this browser on this device using IndexedDB. They are not synced to other devices. Keep your original files backed up because browser storage can be cleared.
- The service worker caches the app files so the interface can reopen offline. It does not download online streaming catalogs or cache remote streaming audio.
- Links to YouTube Music, Spotify, SoundCloud, and Bandcamp open those services; they do not copy their catalogs into this app.

## The eight genres
OPM, Pop, Hip-hop / Rap, Phonk, EDM, Rock, Lo-fi / Chill, Gaming.

## Daniel Caesar artist spotlight
The app includes links to Daniel Caesar album/EP searches and official/authorized music services. The tracks themselves are streamed by those services and are not bundled in this project.
