# slicr

A minimal PWA for splitting an investment amount 70/30 between FZROX and FZILX (Fidelity Zero funds).

Live: https://slicr.netlify.app

Auto-deploys from `main` via Netlify <-> GitHub integration.

## Deploy

This repo is linked to Netlify and auto-deploys from `main`.

## Local preview

Open `index.html` in a browser. Service worker and manifest will only fully activate when served over HTTPS or `localhost`.

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
