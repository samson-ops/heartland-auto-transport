# Heartland Auto Transport — Website

Alabama-based auto transport company website. Static HTML site, ready to deploy.

## Files

- `index.html` — the homepage (single-file site, all CSS inline)
- `images/logo.png` — company logo
- `images/hero-truck.jpg` — hero section background photo

## How to Deploy

This is a static site — no build step, no server needed. Upload these files as-is.

### Cloudflare Pages (recommended, free)
1. Push this folder to a GitHub repo
2. Connect the repo to Cloudflare Pages (Workers & Pages → Create → Pages → Connect to Git)
3. Build settings: Framework = None, Build command = blank, Output directory = blank
4. Deploy

### Any other host
Drag and drop the three files (preserving the `images/` subfolder) into Netlify, Vercel, GitHub Pages, or any traditional web host.

## Updating

To replace a photo: drop a new file in `images/` with the same filename.
To edit text: open `index.html` in any text editor (Notepad, VS Code) and find/replace.

## Notes

- The "Get Instant Pricing" button has `id="instant-pricing-btn"` with `href="#"` — swap the `#` for your real instant pricing URL when ready.
- Phone number `(888) 123-4567` appears in 3 places — search and replace with your real number.
- USDOT number `3981238` is a placeholder — update with your real number.
