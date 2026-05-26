# My AI Automation Lab

Simple static landing page designed for GitHub Pages.

## Local setup

No build step is required.

1. Clone the repository.
2. Open `/home/runner/work/ai-agent-test-page/ai-agent-test-page/index.html` in a browser.

## GitHub Pages deployment

Deployment is handled by `.github/workflows/deploy-pages.yml`.

- The workflow runs on pushes to `main` (and can be run manually).
- It publishes the repository root as a GitHub Pages artifact.

To enable Pages in GitHub:

1. Open **Settings → Pages** in the repository.
2. Set **Source** to **GitHub Actions**.