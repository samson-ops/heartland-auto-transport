# Heartland Auto Transport — Website

Alabama-based auto transport company website. Static HTML site, ready to deploy.

## Files

- `index.html` — the homepage (single-file site, all CSS inline)
- `images/logo.png` — company logo
- `images/hero-truck.jpg` — hero section background photo
- `images/service-open.jpg` — Open Auto Transport service card
- `images/service-enclosed.jpg` — Enclosed Auto Transport service card
- `images/service-nationwide.jpg` — Nationwide Transport service card
- `images/service-expedited.jpg` — Expedited Shipping service card

## How to Deploy

This is a static site — no build step, no server needed. Upload these files as-is.

### Cloudflare Pages (recommended, free)
1. Workers & Pages → Create → Pages tab → Upload assets
2. Project name: `heartlandautotransport` (becomes heartlandautotransport.pages.dev)
3. Drag the contents of this folder (index.html, images/) into the upload area
4. Click Deploy site

### Any other host
Drop these files (preserving the `images/` subfolder) into Netlify, Vercel, GitHub Pages, or any traditional web host.

## Updating

To replace a photo: drop a new file in `images/` with the same filename.
To edit text: open `index.html` in any text editor and find/replace.

## Notes / Placeholders to Update

- The "Get Instant Pricing" button has `id="instant-pricing-btn"` with `href="#"` — swap the `#` for your real instant pricing URL when ready.
- Phone number `(888) 123-4567` appears in 3 places — search and replace with your real number.
- Email `info@heartlandautotransport.com` in the footer — update if different.
- To add your real USDOT/MC number later: search for "FMCSA Licensed Broker" in `index.html` and append your number (e.g. "FMCSA Licensed Broker USDOT 1234567").
