# UbiComp / ISWC 2026 Tutorial Website

A lightweight static website for:

**Towards Open-Sourced Datasets, Benchmarks, and Platforms for Multi-Modal Sensing**

## Files

- `index.html` — main one-page website
- `assets/style.css` — responsive styling
- `.nojekyll` — prevents GitHub Pages from processing the site with Jekyll

## Preview locally

Open `index.html` directly in a browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Upload these files to a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder.
5. Save.

## Items to update later

Search `index.html` for `TODO`. In particular, update:

- exact tutorial date and time;
- conference venue;
- registration URL;
- final material links;
- final tutorial website URL;
- organizer photos, if desired.

The page currently uses Google Fonts. Remove the two Google Fonts `<link>` elements in `index.html` if a fully self-contained site is preferred.
