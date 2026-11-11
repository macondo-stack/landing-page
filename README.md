# landing-page

Static landing page for the [macondo-stack](https://github.com/macondo-stack) study group, served with GitHub Pages.

- `index.html`: the page
- `assets/style.css`: styles (light and dark mode)

## Run locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish

Repository **Settings → Pages → Build and deployment**: source "Deploy from a branch", branch `main`, folder `/ (root)`.
The site is then served at `https://macondo-stack.github.io/landing-page/`.
