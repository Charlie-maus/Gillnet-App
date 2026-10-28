# Estuarine Gillnet App

Offline field app for estuarine gillnet surveys. Runs on iPad (Safari) and Android tablets (Chrome) once installed from GitHub Pages.

## Put it online (GitHub Pages)
1. On GitHub, create a new repository, e.g. `Estuarine-Gillnet-App`.
2. Upload everything in this folder (keep the `icons` folder as a folder).
3. Repository Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. After a minute the app is live at `https://<your-username>.github.io/Estuarine-Gillnet-App/`.

## Install on a tablet
- **iPad:** open the link in Safari → Share → Add to Home Screen.
- **Android (Samsung):** open the link in Chrome → ⋮ menu → Add to Home screen / Install app.

Open it once while online. After that it works with no signal.

## Updating the app
1. Replace `index.html` in the repository with the new version.
2. In `sw.js`, change `VERSION` (e.g. `gillnet-v1` → `gillnet-v2`) and upload it too.
3. On each tablet, open the app while online, close it and open it again to load the update.
Data already saved on the tablet is kept through updates.

## Data
- Records are stored on the tablet only, per device. Export from the Export tab (CSV) after each trip.
- Deleting the home-screen app or clearing the browser's website data deletes unexported records.
