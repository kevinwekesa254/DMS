# DMS Website

Marketing site for **Data Management Systems (Pvt) Ltd** — POS, payments and
business management systems for retail, restaurants and hospitality in Sri Lanka.

Static site: a single `index.html` plus self-hosted assets. No build step.

## Structure

    index.html          the page (markup, styles, and inline app script)
    assets/brand/       DMS logo and partner brand marks
    assets/fonts/       self-hosted woff2 webfonts
    assets/hw/          hardware product shots (Y10 … Y7000)
    assets/icons/       UI icons
    assets/opt/         photography
    assets/js/          design-system runtime and helpers
    assets/vendor/      React 18.3.1 UMD builds

## Local preview

    python3 -m http.server 8000

Then open http://localhost:8000.

## Deployment

Deployed on Vercel as a static site; pushes to `main` deploy automatically.
