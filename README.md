# Concrete Calculator

Works out how much concrete and rebar a rectangular slab with a thickened perimeter footing needs.

- **Concrete:** slab length and width, slab thickness, footing width and depth below the slab, and a waste allowance. Gives cubic yards to order (rounded up to the nearest ¼ yd), a slab/footing breakdown and premix bag counts.
- **Rebar:** slab grid (bar size, spacing, edge cover), continuous footing bars, stick length, lap splice and waste. Gives sticks and pounds to buy per bar size, plus a cut list.

It's a single static page, `site/index.html`, with no build step. Every push to `main` publishes it to GitHub Pages (`.github/workflows/deploy.yml`). Inputs are remembered in the browser's local storage.

To run it locally, open `site/index.html` in a browser.
