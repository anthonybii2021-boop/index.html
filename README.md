# Signalworks AI

Landing page for **Signalworks AI** — custom AI agents for customer support, scheduling, and lead follow-up, built by Anthony Kipkoech Bii (Nairobi, Kenya).

## What this is

A single self-contained `index.html` file — no build step, no dependencies beyond a Google Fonts import. All CSS and JavaScript are inline.

## Running locally

Just open `index.html` in a browser, or serve it with any static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying

This repo is set up for **GitHub Pages**:

1. Go to **Settings → Pages**
2. Under "Branch," select `main` and folder `/ (root)`
3. Save — the site will be live at `https://<username>.github.io/<repo-name>/`

To use a custom domain instead, add a `CNAME` file with your domain name, and point your domain's DNS to GitHub Pages.

## To-do before this is fully live

- [ ] Register a domain and update the `<link rel="canonical">` tag and `og:url` meta tag in `index.html`
- [ ] Replace the placeholder case studies in the **Results** section with real client outcomes
- [ ] Add real demo videos to the **Demo Reel** section (currently marked "coming soon")

## Contact

anthonybii2021@gmail.com · +254 720 050 886
