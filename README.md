# Hridhav's First Year — Milestone Journal PWA

Week-by-week baby development journal. Installable, works offline, saves everything per device — and fully shareable: any parent can open the app, tap the sliders icon in the header, and set their own baby's name, sex, birth date & time, and due date. Pronouns, ages, week calculations, leap forecasts, and WHO growth data (boys/girls) all adapt instantly. Defaults to Hridhav (born June 16, 2026).

## What's inside
- 52 weeks of point-form notes: body, senses, mind, feelings, and parent tips
- Vision panel per week: focus distance diagram + a simulation of what Hridhav actually sees
- 24-hour sleep map, feeding amounts, and diaper norms for each stage
- WHO growth chart (boys, 50th percentile) with the current month marked
- Leaps view: the mental-leaps framework with a 52-week storm/sunshine forecast, current weather status, and 7 expandable leap cards (storm signs, new skills, how to help)
- Leap timing counts from the due date (editable in the Leaps tab, saved per device)

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
