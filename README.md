# Heartland Auto Transport — Website

Alabama-based auto transport company website. Static HTML site, ready to deploy.

## Structure

```
heartland-site/
├── index.html                                 ← homepage
├── styles.css                                 ← shared stylesheet (all pages use this)
├── sitemap.xml                                ← SEO sitemap (submit to Google Search Console)
├── robots.txt                                 ← search engine crawl directives
├── README.md
├── images/
│   ├── logo.png                               ← Heartland logo (trimmed, no whitespace)
│   ├── hero-truck.jpg                         ← homepage hero photo
│   ├── usa-map.jpg                            ← coverage map
│   ├── service-open.jpg                       ← Open Transport card
│   ├── service-enclosed.jpg                   ← Enclosed Transport card
│   ├── service-nationwide.jpg                 ← Nationwide Transport card
│   └── service-expedited.jpg                  ← Expedited Shipping card
└── services/
    ├── open-auto-transport.html               ← 1,400+ words, SEO-optimized
    ├── enclosed-auto-transport.html           ← 1,300+ words, SEO-optimized
    ├── door-to-door-auto-transport.html       ← 1,400+ words, SEO-optimized
    ├── expedited-auto-transport.html          ← 1,400+ words, SEO-optimized
    ├── cross-country-car-shipping.html        ← 1,400+ words, SEO-optimized
    ├── state-to-state-car-shipping.html       ← 1,500+ words, SEO-optimized
    ├── nationwide-auto-transport.html         ← 1,300+ words, SEO-optimized
    ├── terminal-to-terminal-shipping.html     ← 1,500+ words, SEO-optimized
    └── guaranteed-pickup-services.html        ← 1,600+ words, SEO-optimized
```

## SEO Setup

Every page includes:
- Unique `<title>` and meta description targeting service-specific keywords
- Canonical URL
- Open Graph + Twitter Card meta tags
- Schema markup: LocalBusiness, Service, FAQPage, BreadcrumbList
- Geo-targeting for Alabama (US-AL)
- Semantic HTML hierarchy (one H1, multiple H2s, proper H3s)
- Internal linking between related service pages
- Mobile-responsive design

After deploying, submit `sitemap.xml` to Google Search Console for fastest indexing:
https://search.google.com/search-console

## How to Deploy

This is a static site — no build step, no server needed.

### Cloudflare Pages (recommended, free)
1. Workers & Pages → Create → Pages tab → Upload assets
2. Project name: `heartlandautotransport` → becomes heartlandautotransport.pages.dev
3. Drag the contents of this folder into the upload area
4. Click Deploy site

### Any other host
Drop these files (preserving the `images/` and `services/` subfolders) into Netlify, Vercel, GitHub Pages, or any traditional web host.

## Updating

- **CSS changes:** edit `styles.css` once — applies to all 10 pages instantly
- **Replace a photo:** drop a new file in `images/` with the same filename
- **Edit text:** open the relevant `.html` file in any text editor

## Notes / Placeholders to Update

- The "Get Instant Pricing" button has `id="instant-pricing-btn"` with `href="#"` — swap the `#` for your real instant pricing URL when ready.
- Phone number `(888) 123-4567` appears across all pages — search and replace with your real number using your text editor.
- Email `info@heartlandautotransport.com` in footers — update if different.
- To add your real USDOT/MC number: search for "FMCSA Licensed Broker" across all files and append your number.

## Service Page Keywords Targeted

| Page | Primary Keyword | Word Count |
|------|----------------|-----------|
| Open Auto Transport | "open auto transport" + Alabama variations | 1,461 |
| Enclosed Auto Transport | "enclosed auto transport" + classic/exotic | 1,385 |
| Door-to-Door | "door-to-door auto transport" | 1,404 |
| Expedited | "expedited auto transport" | 1,437 |
| Cross Country | "cross country car shipping" | 1,436 |
| State-to-State | "state to state car shipping" | 1,597 |
| Nationwide | "nationwide auto transport" | 1,375 |
| Terminal-to-Terminal | "terminal to terminal shipping" | 1,501 |
| Guaranteed Pickup | "guaranteed pickup services" | 1,656 |

All content is unique per page (no duplicate content penalty), and each page has its own FAQ schema for Google rich snippets.
