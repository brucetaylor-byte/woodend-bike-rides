# Woodend Rides (demo PWA)

Static site: `index.html`, `manifest.webmanifest`, `sw.js`, two icons. No build step.

## Put it on GitHub Pages
1. Create a new repo (e.g. `woodend-rides`) and upload all files in this folder to the root.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`. Save.
3. After a minute it's live at `https://<your-username>.github.io/woodend-rides/`.
4. Rider area (not linked anywhere): add `#riders` to the end of that address.

## Install on a phone
- iPhone (Safari): Share → Add to Home Screen.
- Android (Chrome): menu → Install app.

## Demo limits
Data is stored in the browser on each device (seeded with three sample riders), so two phones don't see each other's bookings. Use "Reset demo data" in the rider area to start over. A shared live version needs a backend (e.g. Firebase or Supabase).
