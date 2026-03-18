# waveform

This repo is configured to deploy to **GitHub Pages** using GitHub Actions.

## What was added
- `index.html` as the Pages entrypoint (copied from `stemviz-xr.html`)
- `.github/workflows/deploy-pages.yml` for automatic deployment on pushes to `main`
- `.nojekyll` so files are served directly without Jekyll processing

## One-time GitHub setup
In your GitHub repository settings:
1. Go to **Settings → Pages**
2. Under **Build and deployment**, choose **Source: GitHub Actions**

After that, every push to `main` will trigger a Pages deployment.
