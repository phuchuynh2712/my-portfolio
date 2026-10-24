# Portfolio of Huỳnh Hữu Phúc

A static site: plain HTML, CSS and a few lines of JavaScript. There is no build step.

- `index.html`: home page
- `finance/index.html`: case study of the Finance app
- `assets/`: styles, script and images

## Run locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000/.

## Deploy

GitHub Pages serves the `main` branch from the repository root. Pushing to `main` redeploys the site.
The canonical URLs, `sitemap.xml` and `404.html` assume the address `https://phuchuynh2712.github.io/my-portfolio/`.
If the repository is renamed or a custom domain is added, update those three places.

## Notes

- Client products are shown as illustrative mockups, never real screenshots.
- The Finance screenshots are renders of the real app with sample data.
