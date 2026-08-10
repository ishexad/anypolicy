# AnyPolicy

Policy drafting & review, by jurisdiction — a static, dependency-free prototype
of the AnyPolicy site (landing, pricing, sign-in, and the draft/review policy
wizards), built as a single `index.html` with vanilla CSS/JS.

## Deployment

This repo deploys automatically to GitHub Pages via
[`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) on every push
to `main`. Once the first workflow run completes, the site is live at:

```
https://ishexad.github.io/anypolicy/
```

If Pages isn't already enabled for this repository, do it once at
**Settings → Pages → Build and deployment → Source: GitHub Actions** (the
workflow's `actions/configure-pages` step will also attempt this
automatically on first run).

## Local preview

No build step required — just open `index.html` in a browser, or serve it:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
