# Altadena 91001 Recovery Tracker

Post-Eaton Fire market intelligence dashboard tracking land values, rebuilding costs, permit progress, and market correlations for Altadena, CA 91001.

## Deploy to GitHub Pages (5 minutes)

### Option A: Quick Deploy (Browser Only)

1. Go to [github.com/new](https://github.com/new) and create a new repository (e.g. `altadena-dashboard`)
2. Upload `index.html` to the repo (drag and drop, or use "Add file" → "Upload files")
3. Go to **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose **main** branch, **/ (root)** folder, click **Save**
6. Wait ~60 seconds — your live URL will appear at: `https://YOUR-USERNAME.github.io/altadena-dashboard/`

### Option B: Command Line

```bash
git init
git add index.html README.md
git commit -m "Altadena 91001 Recovery Tracker"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/altadena-dashboard.git
git push -u origin main
```

Then enable GitHub Pages in Settings → Pages → Deploy from main branch.

## Features

- **Land Values** — Active lot listings, recent sales comps, 30-day sales data, price/sq ft for fire-cleared lots
- **Rebuilding Costs** — Tiered cost visualization, full line-item breakdown, fixed-price turnkey options
- **Permits** — LA County permit progress with timeline charts, progress rings, monthly breakdown
- **Correlation** — Multi-line chart overlaying permits, build costs, lot prices, and sale prices
- **Build Calculator** — Interactive cost estimator with tier selection and ADU toggle
- **AI Live Refresh** — Anthropic API web search for real-time data updates
- **Download Report** — Exportable plain-text summary of all data

## Data Sources

Redfin, Zillow, LandSearch, LandWatch, Homes.com, ATTOM, GreatBuildz, Kyra Construction, GO Home Builders, Genesis Builders, LA County Recovery Dashboard, CalMatters, NBC Los Angeles, HeySoCal, Urban Land Institute, LA Public Press, Marketplace.org

## Tech

Single-file React app — no build step required. Uses React 18 + Babel standalone via CDN.

Data as of: April 1, 2026
