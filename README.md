# Glitch Field

Self-contained browser-based generative black-and-white glitch art, inspired by the visual language of dense, orthogonal, fractured poster graphics. No artwork or typography is copied, and no dependencies are required.

## Run

Open `index.html` in your browser. Or serve as a static site:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Controls

- **New composition** / **Space**: generate a new seed.
- **Complexity**: amount of nested contour and stripe geometry.
- **Disruption**: intensity of horizontal slice displacement.
- **Seed**: type any number to reproduce a composition.
- **Animate**: automatically change seed every 850 milliseconds.
- **Export PNG** / **S**: export full-resolution 1400 × 2000 artwork, without UI or text.

## Deployment

Static site: place the `index.html` anywhere in a GitHub Pages, Caddy, or other static web root. No npm, build process, backend, or server permissions needed.
