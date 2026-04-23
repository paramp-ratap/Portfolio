# Responsive Portfolio Website

A UI-heavy, responsive portfolio site generated from the provided LaTeX resume content.

## Local Run

Because this is a static website, you can run it with any static server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml` that deploys the site to **GitHub Pages** whenever code is pushed to the `main` branch.

### One-time setup steps (GitHub)

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Set **Build and deployment** source to **GitHub Actions**.
4. Push to `main` (or re-run the workflow manually from **Actions** tab).

After successful workflow completion, GitHub Pages will publish the live URL.
