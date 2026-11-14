# fws

Farmwagon's graphic, classroom-edition storefront. All styling, JavaScript, product illustrations, routing, and ordering interactions are embedded in `index.html`; no dependencies or build step are needed.

Open `index.html` directly in a modern browser, or serve this directory with `python -m http.server 8000` and visit `http://localhost:8000`.

The site opens with a nostalgic seat chooser:

- **Jugaadu Backbenchers**
- **Creative Middle Row**
- **Topper Front Row**

Each choice applies a distinct visual treatment and voice while preserving the same product facts. The storefront includes dedicated single-page routes for raw makhana (`#product-raw`), flavoured makhana (`#product-flavoured`), and moringa leaf powder (`#product-moringa`), with selectable flavours and pack sizes.

The mobile-first order bag persists locally, updates quantities and subtotals, and uses the native share sheet on supported iOS and Android devices. Browser back/forward navigation, direct links, touch-sized controls, safe-area insets, and reduced-motion preferences are supported.

## Free hosting with GitHub Pages

In this repository's **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source. Pushes to `main` run the **Deploy website to GitHub Pages** workflow and publish the site at <https://cppxaxa.github.io/fws/>. The workflow can also be run manually from the Actions tab. Only `index.html` is included in the published artifact.
