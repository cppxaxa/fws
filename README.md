# fws

Farmwagon company demo page. A single `index.html` plus campaign photos in `images/`. No dependencies or build step.

Open `index.html` in a modern browser, or serve this directory with `python -m http.server 8000` and visit `http://localhost:8000`.

The live page is a logo-free product site: a harvest banner, raw makhana, flavoured makhana, and a company footer. There is no classroom / seat story on the published page.

This is a public learning demo for collaborators, not a live shop. See [NOTICE.md](NOTICE.md).

## Free hosting with GitHub Pages

In this repository's **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source. Pushes to `main` run the **Deploy website to GitHub Pages** workflow and publish the site at <https://cppxaxa.github.io/fws/>. The workflow can also be run manually from the Actions tab. The published artifact includes `index.html` and `images/`.
