# Consult — Demo

Static, single-file demo (HTML/CSS/JS). No build step, no backend, no dependencies.
All patient data is fictional and held in memory — refreshing the page resets it.

## Run locally
Open `index.html` in a browser, or serve the folder:
    npx serve .

## Deploy (any static host)
- Netlify: drag this folder onto app.netlify.com/drop
- Vercel: `npx vercel` in this folder
- Cloudflare Pages / GitHub Pages: upload `index.html` as the site root
- AWS S3: upload `index.html`, enable static website hosting (or front with CloudFront)
