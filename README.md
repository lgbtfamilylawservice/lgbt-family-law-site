# The LGBT Family Law Service — Website

Affiliate referral website for The LGBT Family Law Service.
Available 24/7. Toll-free: (855) 218-9853.

## Stack

Plain static HTML/CSS — no build step. Deployed via GitHub → Netlify.

## Structure

```
/
├── index.html                # Homepage
├── robots.txt
├── sitemap.xml
├── assets/
│   ├── css/styles.css        # Site styles (all pages share)
│   ├── js/                   # (reserved for future scripts)
│   └── img/
│       ├── logo.svg          # Header logo (placeholder, replace with logo.png if preferred)
│       └── favicon.svg
```

## Local preview

The simplest way to preview locally:

```bash
cd lgbt-family-law-site
python -m http.server 8000
# open http://localhost:8000
```

Or use the VS Code "Live Server" extension on `index.html`.

## Deploy

Connected to Netlify via the `main` branch of this repo. Every push to main
triggers a production deploy.

## Affiliate disclosure

This site is a referral and information service, not a law firm. No legal
advice or services are provided directly. See `disclaimer/`, `terms-of-service/`,
and `privacy-policy/` pages.
