# First Year — Baby Journal (PWA)

Week-by-week baby development journal with daily tracking. Installable, works offline, saves everything per device. Fully shareable: any parent taps the sliders icon in the header and sets their own baby's name, sex, birth date & time, and due date — pronouns, ages, leap forecasts, and WHO growth data (boys/girls) all adapt. Defaults to Hridhav (born June 16, 2026).

## Tabs
- **Today** — leap weather, this week's headline, quick log (feed / diaper / sleep timer) with today's counts vs. what's typical for this stage, what's coming up, and a dated list of firsts
- **Journal** — 52 weeks of point-form notes: body, senses, mind, feelings, tips; vision simulator + focus distance; 24h sleep map; feeding amounts; diaper norms; growth marker; milestone checklist (dated when ticked); red flags; notes for the week
- **Leaps** — mental-leaps framework: 52-week storm/sunshine forecast, current status, 7 expandable leap cards (counts from due date)
- **Log** — 7-day charts (feeds, wet diapers, sleep) against typical bands, plus full history with delete
- **Growth** — enter weight / length / head at checkups; plotted on WHO 3rd–97th percentile bands with an estimated percentile
- **Health** — Ontario immunization schedule and Rourke well-baby visits with due dates, done-dates, and a "questions for the doctor" notepad

## Backup & moving phones
Header → sliders icon → Export copies a backup to the clipboard; paste it into the same box on another phone and tap Restore. Data is per device (no server, no account).

## Deploy to GitHub Pages
1. Upload all files in this folder to the repository root
2. Settings → Pages → Deploy from a branch → main / root
3. Open `https://<username>.github.io/<repo>/` and Add to Home Screen

## Updating
After editing `index.html`, bump the cache name in `sw.js` (e.g. `firstyear-v5` → `firstyear-v6`) so installed devices fetch the new version.

## Sources
CDC "Learn the Signs. Act Early." (2022) · AAP HealthyChildren.org · WHO Child Growth Standards · NHS Start for Life · Zero to Three · Ontario immunization schedule · Rourke Baby Record. General information, not medical advice.
