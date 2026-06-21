# Cleared Capital — Landing Page

Static landing page for Cleared Capital (South African prop trading firm). Single file: `index.html`, with image assets alongside it.

## Run locally
```
python -m http.server 8000
```
Then open http://localhost:8000/

## Files
- `index.html` — the whole landing page (styles + markup + JS inline)
- `bull.png`, `hand.png`, `hand-flip.png`, `gold.png` — feature-card images
- `predict-card.png` — Predict-the-Price promo card
- `cleared-mark.svg`, `favicon.svg` — logo mark + favicon

## Notes
- Feature cards use full-width image bleeds from the right with a left-fade mask (`fc-bull`, `fc-hand`, `fc-gold`).
- Staging only — `index.html` has `noindex` set.
