---
marp: true
theme: default
paginate: true
---

# Hogakusten2026

Marp-powered project presentation published with GitHub Pages.

---

## What this repository does

- Stores the presentation source in `README.md`
- Uses Marp CLI in CI to generate slide output
- Publishes generated slides as a GitHub Pages site

---

## How publishing works

1. Push changes to `README.md`
2. GitHub Actions generates `index.html` from this file
3. The workflow deploys the artifact to GitHub Pages

---

## Local preview

```bash
npm ci
npm run build:slides -- --output dist/index.html
```

Open `dist/index.html` in a browser to preview the slides locally.
