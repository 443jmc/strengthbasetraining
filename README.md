# Strength Base Training

Single-page site for [strengthbasetraining.com](https://strengthbasetraining.com), hosted on Cloudflare Pages and deployed from this repo.

## Structure

- `index.html` — the page
- `styles.css` — all styles (sage + gold palette matching Strength-Based Marriage, Playfair Display + Inter)
- `script.js` — mobile nav toggle + scroll shadow
- `_headers` — Cloudflare Pages cache headers

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy

Push to `main`. Cloudflare Pages is connected to this repo and auto-deploys on push, with `strengthbasetraining.com` as the custom domain.
