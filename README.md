# fws

Farmwagon's classroom-edition makhana website. All styling, JavaScript, and SVG illustrations are embedded in `index.html`; no dependencies or build step are needed.

Open `index.html` directly in a modern browser, or serve this directory with `python3 -m http.server 8000` and visit `http://localhost:8000`.

Choose a seat to explore one of three product experiences. The landing page automatically selects the front row after 40 seconds. Each experience includes a return button, supports browser back/forward navigation and direct links (`#back`, `#middle`, `#front`), and respects reduced-motion preferences.

## Free hosting with GitHub Pages

In this repository's **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source. After these changes are merged into `main`, the **Deploy website to GitHub Pages** workflow publishes the site at <https://cppxaxa.github.io/fws/>. Subsequent pushes to `main` deploy automatically; you can also run the workflow manually on `main` from the Actions tab. Only `index.html` is included in the published artifact.
