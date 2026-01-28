# Dreelio (Framer-inspired) — Static HTML

This folder contains a static HTML/CSS/JS recreation focused on the **/blog** page (plus 4 post pages).

## Structure

- `index.html` — minimal landing placeholder
- `blog/index.html` — blog listing (matches the Framer layout)
- `blog/*.html` — 4 blog post pages
- `assets/styles.css`
- `assets/app.js`

## Run locally

Just open `index.html` or use a local server:

```bash
# python
python -m http.server 8000
```

Then open `http://localhost:8000/` and `http://localhost:8000/blog/`.

## Deploy to GitHub Pages

Upload everything to your repo root, enable Pages, and set:
- Build: `Deploy from a branch`
- Folder: `/ (root)`
