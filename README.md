# confusedkernel.github.io

Personal GitHub Pages site: an index of all projects with a GitHub page.

Live at https://confusedkernel.github.io

## Structure

- `index.html` – the entire site (single static page)
- `.nojekyll` – tells GitHub Pages to skip Jekyll processing

## Local development

No build step. Open `index.html` in a browser, or serve it locally:

```sh
python3 -m http.server 8000
```

## Deployment

Pushing to `main` runs `.github/workflows/deploy.yml`, which publishes the site via GitHub Actions. It can also be run manually from the Actions tab.

One-time setup: in the repo's **Settings → Pages**, set **Source** to **GitHub Actions**.
