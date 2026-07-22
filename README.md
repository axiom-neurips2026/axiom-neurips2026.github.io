# AXIOM 2026 workshop website

Static GitHub Pages website for the AXIOM NeurIPS 2026 workshop.

## Publish

1. Upload all files in this folder to the root of `axiom-neurips2026/axiom-neurips2026.github.io`.
2. In GitHub, open **Settings → Pages**.
3. Select **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save and wait a few minutes.

## Customize first

- Replace all placeholder text in `index.html`.
- Save the hero image as `images/hero.jpg`.
- Replace placeholder speaker and organizer blocks with real image paths.
- Update dates, affiliations, email address, and submission links.
- Keep `.nojekyll` in the repository root.

## Local preview

Run from this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
