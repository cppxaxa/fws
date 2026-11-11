# fws

Farmwagon's classroom-edition makhana website. All styling, JavaScript, and SVG illustrations are embedded in `index.html`; no dependencies or build step are needed.

Open `index.html` directly in a modern browser, or serve this directory with `python3 -m http.server 8000` and visit `http://localhost:8000`.

Choose a seat to explore one of three product experiences. The landing page automatically selects the front row after 40 seconds. Each experience includes a return button, supports browser back/forward navigation and direct links (`#back`, `#middle`, `#front`), and respects reduced-motion preferences.
