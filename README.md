# az-clean-preview

This is the built output for [azclean.gr](https://azclean.gr) — no source code here, just the static `index.html`, JS/CSS bundle, and image assets that GitHub Pages serves directly from this repo's `main` branch (custom domain configured via the `CNAME` file).

The actual React/Vite source lives in a separate repository. This repo gets updated by copying in a fresh production build after changes are made there — it isn't wired to a CI workflow, so an update here is a manual step, not automatic.
