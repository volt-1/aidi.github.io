# aidi.github.io

This repository contains a simple personal website inspired by the minimalist look of Real Life Magazine. Open `index.html` in a browser to view the site.

## Publishing with GitHub Pages

After pushing this repository to GitHub, enable **GitHub Pages** under your
repository's **Settings** > **Pages**. Choose **GitHub Actions** as the
deployment source so the workflow in `.github/workflows/gh-pages.yml` can
publish the site automatically. Once enabled, the site will be served at:

```
https://volt-1.github.io/aidi.github.io/
```

The `.nojekyll` file ensures the site is treated purely as static HTML without
Jekyll processing.
