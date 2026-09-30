# Colorado Fall Road Trip App

A shareable, mobile-friendly trip dashboard for the Oct 9–11, 2026 Colorado road trip:

- Day 1: Denver → Twin Lakes → Independence Pass → Aspen → Maroon Bells
- Day 2: Aspen → Glenwood Springs → Vail → Denver
- Day 3: Denver → Rocky Mountain National Park → Estes Park → Denver

The app includes the day-by-day plan, route overview, restaurants, scenic/photo stops, reservation links, lodging guidance, and trip notes.

## Run locally

No build step is required. Open `index.html` in a browser.

The page loads React, ReactDOM, and Babel from public CDNs, so an internet connection is required for the app to render.

## Automatic GitHub Pages deployment

This repository includes `.github/workflows/deploy-pages.yml`. Every push to the `main` branch automatically publishes the latest app to GitHub Pages. You can also run the workflow manually from the **Actions** tab.

### One-time GitHub setup

1. Create a GitHub repository, for example `colorado-trip`.
2. Upload/extract all files from this package into the repository, preserving the `.github/workflows/` folder.
3. Push or commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment → Source**, select **GitHub Actions**.
6. Open the **Actions** tab and wait for `Deploy Colorado Trip App to GitHub Pages` to finish.

The public site will normally be available at:

`https://YOUR-USERNAME.github.io/colorado-trip/`

After that, simply push changes to `main`; no manual Pages deployment is needed.

## Files

- `index.html` — complete trip app
- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment
- `README.md` — setup instructions
- `.nojekyll` — serves the repository as a plain static site

## Notes

Mountain weather, road access, restaurant hours, and reservation availability can change. Recheck official sources shortly before the trip, especially Independence Pass, Maroon Bells, and Rocky Mountain National Park.
