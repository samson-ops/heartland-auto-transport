# Heartland Auto Transport — Website

Alabama-based auto transport company website. Static HTML site, ready to deploy.

## Site Stats

- **25 total pages** (1 homepage + 24 service pages)
- **All pages SEO-optimized** with unique titles, meta, schema markup
- **1,044 - 1,656 words** per service page (all original content)
- **One shared `styles.css`** — edit once, applies everywhere
- **Mobile responsive**, fast-loading static HTML

## Structure

```
heartland-site/
├── index.html
├── styles.css
├── sitemap.xml                            ← submit to Google Search Console
├── robots.txt
├── README.md
├── images/
│   ├── logo.png
│   ├── hero-truck.jpg
│   ├── usa-map.jpg
│   ├── service-open.jpg
│   ├── service-enclosed.jpg
│   ├── service-nationwide.jpg
│   └── service-expedited.jpg
└── services/                              ← 24 service pages
    │
    │   ── Shipping Methods (9) ──
    ├── open-auto-transport.html               1,461 words
    ├── enclosed-auto-transport.html           1,385 words
    ├── door-to-door-auto-transport.html       1,404 words
    ├── expedited-auto-transport.html          1,437 words
    ├── cross-country-car-shipping.html        1,436 words
    ├── state-to-state-car-shipping.html       1,597 words
    ├── nationwide-auto-transport.html         1,375 words
    ├── terminal-to-terminal-shipping.html     1,501 words
    ├── guaranteed-pickup-services.html        1,656 words
    │
    │   ── Vehicle Types (15) ──
    ├── car-shipping.html                      1,188 words
    ├── suv-transport.html                     1,116 words
    ├── truck-shipping.html                    1,059 words
    ├── motorcycle-shipping.html               1,044 words
    ├── electric-vehicle-shipping.html         1,172 words
    ├── luxury-car-transport.html              1,079 words
    ├── exotic-car-transport.html              1,131 words
    ├── classic-car-transport.html             1,173 words
    ├── antique-vehicle-shipping.html          1,187 words
    ├── rv-transport.html                      1,284 words
    ├── boat-transport.html                    1,358 words
    ├── atv-utv-shipping.html                  1,160 words
    ├── golf-cart-shipping.html                1,281 words
    ├── van-transport.html                     1,204 words
    └── heavy-equipment-transport.html         1,356 words
```

## SEO Setup (every page)

- Unique `<title>` and meta description targeting the page's primary keyword
- Canonical URL, Open Graph and Twitter Card meta
- Schema markup: Service, FAQPage, BreadcrumbList (gets Google rich snippets)
- Geo-targeting Alabama (`geo.region=US-AL`)
- Proper semantic HTML (one H1, multiple H2s/H3s)
- Internal links between related service pages
- Mobile-responsive layout

After your site is live, submit `sitemap.xml` to Google Search Console:
https://search.google.com/search-console

## How to Deploy

This is a static site — no build step, no server needed.

**Cloudflare Pages (recommended, free):**
1. Workers & Pages → Create → Pages tab → Upload assets
2. Project name: `heartlandautotransport` → URL becomes heartlandautotransport.pages.dev
3. Drag the contents of this folder into the upload area
4. Click Deploy site

Works equally well on Netlify, Vercel, GitHub Pages, or any traditional host.

## Updating

- **CSS changes** — edit `styles.css`, applies to all 25 pages
- **Replace a photo** — drop a new file in `images/` with the same filename
- **Edit text** — open the relevant `.html` file in any text editor

## Placeholders to Replace Before Launch

- Phone number `(888) 123-4567` — search & replace across all files
- Email `info@heartlandautotransport.com` — same
- "Get Instant Pricing" button has `id="instant-pricing-btn"` with `href="#"` — swap with your real pricing tool URL
- USDOT/MC number — currently just "FMCSA Licensed Broker"; append your actual number if desired

## Service Page Keywords Targeted

Each page targets a different specific keyword, so all 24 pages can rank separately in Google for their own search terms:

| Page | Primary Keyword |
|------|----------------|
| Open Auto Transport | "open auto transport" |
| Enclosed Auto Transport | "enclosed auto transport" + classic/exotic |
| Door-to-Door | "door-to-door auto transport" |
| Expedited | "expedited auto transport" |
| Cross Country | "cross country car shipping" |
| State-to-State | "state to state car shipping" |
| Nationwide | "nationwide auto transport" |
| Terminal-to-Terminal | "terminal to terminal shipping" |
| Guaranteed Pickup | "guaranteed pickup services" |
| Car Shipping | "car shipping" / "ship my car" |
| SUV Transport | "SUV transport" / "SUV shipping" |
| Truck Shipping | "truck shipping" / "pickup truck transport" |
| Motorcycle Shipping | "motorcycle shipping" / "Harley shipping" |
| EV Shipping | "Tesla shipping" / "EV transport" |
| Luxury Cars | "luxury car transport" |
| Exotic Cars | "exotic car transport" / "Ferrari shipping" |
| Classic Cars | "classic car transport" / "muscle car shipping" |
| Antique Vehicles | "antique car shipping" / "pre-war car transport" |
| RV Transport | "RV transport" / "motorhome shipping" |
| Boat Transport | "boat transport" / "yacht shipping" |
| ATV/UTV | "ATV shipping" / "side by side transport" |
| Golf Carts | "golf cart shipping" |
| Vans | "van transport" / "Sprinter shipping" |
| Heavy Equipment | "heavy equipment transport" / "bulldozer shipping" |

All content is unique per page (no duplicate content penalty). Each page has its own FAQ schema, giving you 24 separate opportunities for Google rich-snippet FAQ displays in search results.
