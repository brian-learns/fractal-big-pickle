# Fractal Big Pickle

Simple single-page fractal generator (Mandelbrot set) with vanilla HTML/JS.

## Tech Stack
- Pure HTML + CSS + JavaScript (no build system)
- Canvas API for rendering
- Deployed via GitHub Pages

## Commands
- No build commands needed - edit `index.html` directly
- To test: open `index.html` in a browser

## Deployment
- GitHub Pages enabled on `main` branch
- Source path: `/` (root)
- URL: https://brian-learns.github.io/fractal-big-pickle/
- Push to `main` to deploy

## Architecture
- Single HTML file: `index.html`
- Color schemes defined in JS object (`colorSchemes`)
- Fractal data cached in `iterationData` Uint8Array for fast color cycling
- Click on canvas to zoom in 2x at click location
