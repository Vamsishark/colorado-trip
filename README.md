# 🏔️ Colorado Fall Loop — Oct 9–11, 2026

A lightweight, mobile-friendly trip dashboard for the optimized Colorado route:

**Denver → Rocky Mountain National Park → Estes Park → Twin Lakes → Independence Pass → Aspen → Maroon Bells → Glenwood Springs → Vail → Denver**

The itinerary puts RMNP first and avoids returning to Denver between sightseeing days.

## 🌐 Live site

After GitHub Pages is enabled:

**https://vamsishark.github.io/colorado-trip/**

## 📅 Itinerary

### Day 1 — Friday, Oct 9
**Denver → RMNP → Estes Park**

- Bear Lake
- Nymph Lake
- Dream Lake
- Optional Emerald Lake
- RMNP scenery / wildlife
- Estes Park
- **Overnight: Estes Park**

### Day 2 — Saturday, Oct 10
**Estes Park → Twin Lakes → Independence Pass → Aspen → Maroon Bells**

- Twin Lakes
- Independence Pass (12,095 ft)
- Aspen
- Maroon Bells
- **Overnight: Aspen**

> Independence Pass is seasonal and weather-dependent. Check live road status before travel.

### Day 3 — Sunday, Oct 11
**Aspen → Glenwood Springs → Glenwood Canyon → Vail → Denver**

- Glenwood Hot Springs
- Glenwood Canyon
- Vail Village
- Return toward DEN
- **Overnight: Denver International Airport area**

### Monday, Oct 12
**10:00 AM flight from DEN**

## ✨ App features

- Offline-safe schematic trip map
- Day-by-day itinerary tabs
- Google Maps navigation links for each driving leg
- RMNP and Maroon Bells reservation links
- Independence Pass road-status link
- Stay strategy
- Indian-food and best-restaurant searches by stop
- Scenic/photo checklist
- October weather, altitude and seasonal-road notes
- Responsive mobile layout

## 🗺️ Why the overview map is reliable

The trip overview is an **embedded SVG**, not a third-party JavaScript map. It therefore renders directly on GitHub Pages and does not depend on a map API key or external tile server.

For real driving/navigation, the dashboard links each route leg directly to Google Maps.

## 🎟️ Important links

- RMNP timed entry: https://www.recreation.gov/timed-entry/10086910
- Maroon Bells: https://www.visitmaroonbells.com/
- Colorado road conditions: https://www.cotrip.org/

## 📁 Project structure

```text
colorado-trip/
├── index.html
├── README.md
├── .nojekyll
└── .github/
    └── workflows/
        └── deploy-pages.yml
```

## 🚀 GitHub Pages deployment

Repository:

**https://github.com/Vamsishark/colorado-trip**

1. Upload the contents of this ZIP to the repository root.
2. Commit to the `main` branch.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **GitHub Actions**.
5. The included workflow will deploy the site automatically.
6. Every future push to `main` triggers another deployment.

## 🔄 Updating

Edit `index.html`, then:

```bash
git add .
git commit -m "Update Colorado trip planner"
git push origin main
```

GitHub Actions handles deployment automatically.

## 🔒 Privacy

Do not commit flight confirmation codes, hotel reservation numbers, phone numbers, IDs, or other private travel details to a public repository.
