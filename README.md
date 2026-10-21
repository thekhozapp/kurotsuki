# kurotsuki.in

The one-page site for **Kurotsuki Private Limited** (黒月, "black moon"), makers of [KHOZ](https://khoz.app).

- `index.html` is the whole site: plain HTML, CSS and JS, with fonts from Google Fonts and no build step.
- Every push to `main` publishes it to GitHub Pages (`.github/workflows/pages.yml`).
- `CNAME` points Pages at `kurotsuki.in`.

## Going live

1. Settings → Pages → Source: **GitHub Actions**.
2. DNS for kurotsuki.in:
   - `A @` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME www` → `thekhozapp.github.io`
3. Once the first deploy is green and DNS has spread, tick **Enforce HTTPS** in Settings → Pages.

To preview locally, open `index.html` in a browser.
