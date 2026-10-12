# Coffee Station

A single-page static site (plain HTML and CSS, no build step) for our shared coffee fund and machine instructions.

## PayPal Pool link

Both buttons in [index.html](index.html) point to the PayPal Pool: `https://www.paypal.com/pool/9qbLBqmO3Y?sr=wccr`. If the pool changes, update both links.

## Deploy to Cloudflare Pages

1. Push this repo to GitHub or GitLab.
2. In the Cloudflare dashboard, go to **Workers & Pages → Create → Pages → Connect to Git** and pick the repo.
3. Build settings:
   - Framework preset: **None**
   - Build command: *(leave empty)*
   - Build output directory: `/`
4. Save and deploy. Every push to `main` redeploys the site.

Alternatively, drag the project folder into **Upload assets** for a one-off direct upload.

## Local preview

Open `index.html` in a browser, or run `python -m http.server` in this folder.
