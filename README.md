# Hridhav's First Year — Milestone Journal PWA

Week-by-week development journal for Hridhav (born June 16, 2026). Installable, works fully offline, saves milestone checkmarks per device.

## Deploy to GitHub Pages

1. Create a new repository (e.g. `hridhav-first-year`)
2. Upload all files in this folder to the repository root:
   `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`, `apple-touch-icon.png`
3. Repository → Settings → Pages → Source: **Deploy from a branch** → Branch: **main** / root → Save
4. Open `https://<your-username>.github.io/hridhav-first-year/`
5. On a phone: Share → **Add to Home Screen** — it installs like an app and works offline afterward

## Updating the app later

Edit `index.html`, then bump the cache version in `sw.js` (`hridhav-v1` → `hridhav-v2`) so installed devices pick up the new version.

## Notes

- All paths are relative, so it works from any repo name or subdirectory
- Milestone checkmarks and the name are stored in each device's localStorage (per-device, not synced)
- Content sources: CDC "Learn the Signs. Act Early." (2022), AAP HealthyChildren.org, WHO, NHS Start for Life, Zero to Three
