# Audibly You AI — proof site

Static site for Audibly You AI. Plain HTML, CSS, and a tiny JS file.
Deploys directly to GitHub Pages from the `main` branch root.

## Pages
- `index.html` — Home
- `about.html`
- `how-it-works.html`
- `personal-ai-profile.html`
- `export-your-profile.html`
- `personalized-ai-courses.html`
- `privacy.html`
- `for-teams.html`
- `pricing.html` — coming-soon hero
- `resources.html` — placeholder cards
- `contact.html`
- `get-started.html`

## Stack
- Plain HTML/CSS/JS (no build step)
- Inter via Google Fonts
- All AI imagery in `assets/images/`
- SVG wordmark inlined in nav and footer; standalone copy at `assets/wordmark.svg`
- Favicon at `favicon.svg`
- `build.py` is the source-of-truth generator for all 12 pages

## Local preview
```
python3 -m http.server 5050
```

Then open http://localhost:5050/
