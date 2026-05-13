# Heartland Auto Transport — Complete Website

Alabama-based auto transport company website. Static HTML, fully SEO-optimized with clean URLs, mobile responsive, ready to deploy.

## Site Stats

- **85 HTML pages** — 1 homepage + 5 utility + 24 city + 45 service + 10 blog posts
- **110,000+ words** of original SEO content
- **Clean URLs** (no `.html` extension shown to users)
- **100% SEO compliance** — every page passes all checks
- **Fully mobile responsive** with functional hamburger menu

## Clean URLs

Your site uses **clean URLs without `.html`** for maximum SEO and a more professional appearance. Visitors see:

- `heartlandautotransport.com/` (homepage)
- `heartlandautotransport.com/about`
- `heartlandautotransport.com/contact`
- `heartlandautotransport.com/cities/birmingham-auto-transport`
- `heartlandautotransport.com/services/dealer-auto-transport`
- `heartlandautotransport.com/blog/snowbird-car-shipping-guide`

Cloudflare Pages automatically handles the routing — serves `/about` when someone visits without the extension. The `_redirects` file also 301-redirects old `.html` URLs to clean versions, preserving any SEO link equity if you've shared `.html` URLs previously.

## What Was Optimized

### SEO Core (every page)
- ✅ Title tag — optimal 30-70 chars (no truncation in Google results)
- ✅ Meta description — optimal 70-160 chars (no truncation)
- ✅ Canonical URL with clean format (no `.html`)
- ✅ H1 tag (one per page)
- ✅ Meta keywords
- ✅ Author meta tag

### Enhanced Search Signals
- ✅ Theme-color meta (`#7a1f2b` maroon — colors mobile browser address bar)
- ✅ Enhanced robots directives (`max-image-preview:large, max-snippet:-1, max-video-preview:-1`)
- ✅ Geo targeting (US-AL specific, Alabama-aware)

### Social Sharing
- ✅ Complete Open Graph (Facebook, LinkedIn, Discord previews)
- ✅ Twitter Card meta tags

### Structured Data
- ✅ Schema.org markup on every page (Service, Article, FAQPage, BreadcrumbList)
- ✅ Rich snippet eligibility (Google can show FAQs, breadcrumbs, ratings inline)

### Mobile Performance
- ✅ Viewport meta with proper scaling
- ✅ Functional hamburger menu (animated → X)
- ✅ JS toggle works on every page (not just homepage)
- ✅ 21 responsive breakpoints
- ✅ Single-column layouts on phones
- ✅ Touch-friendly tap targets
- ✅ Full-width CTAs on mobile

### Crawler Configuration
- ✅ `robots.txt` with sitemap reference and crawler-specific rules
- ✅ Sitemap.xml with 85 URLs (clean format)
- ✅ Priority weighting: homepage (1.0) > cities (0.95) > services (0.9) > utility (0.8) > blog (0.7)

## Folder Structure

```
heartland-site/
├── index.html
├── how-it-works.html
├── about.html
├── faq.html
├── contact.html
├── blog.html
├── styles.css
├── sitemap.xml                 ← 85 clean URLs
├── robots.txt                  ← Enhanced
├── _redirects                  ← Cloudflare Pages redirect rules
├── README.md
│
├── cities/                     ← 24 Alabama city pages
├── services/                   ← 45 service pages
├── blog/                       ← 10 blog posts
└── images/                     ← 7 images
```

## Deploy to Cloudflare Pages

1. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** tab → **Upload assets**
2. Project name: `heartlandautotransport`
3. Drag the contents of this folder into the upload area (Cloudflare automatically uses `_redirects`)
4. Click Deploy site

Your site will be live at `heartlandautotransport.pages.dev` with clean URLs working out of the box. When you add your custom domain, all URLs will work cleanly there too.

## After Deployment

1. Submit `sitemap.xml` to Google Search Console: https://search.google.com/search-console
2. Set up Google Business Profile for local SEO
3. Set up Yelp business page
4. Test rich snippets in Google's Structured Data Testing Tool: https://search.google.com/test/rich-results

## Page Inventory

### Top-Level Pages (6)
- `/` — Homepage
- `/about` — About Heartland
- `/how-it-works` — 5-step process
- `/faq` — Categorized FAQ
- `/blog` — Blog index
- `/contact` — Contact form + info

### Cities (24)
Birmingham, Huntsville, Mobile, Montgomery, Tuscaloosa, Hoover, Auburn, Dothan, Madison, Decatur, Florence, Prattville, Vestavia Hills, Phenix City, Alabaster, Gadsden, Opelika, Northport, Enterprise, Daphne, Athens, Homewood, Trussville, Bessemer

### Services (45)
**Standard Methods:** open, enclosed, door-to-door, expedited, cross-country, state-to-state, nationwide, terminal-to-terminal, guaranteed-pickup

**Vehicle Types:** car, SUV, truck, motorcycle, EV, luxury, exotic, classic, antique, RV, boat, ATV/UTV, golf cart, van, heavy equipment

**Business & Commercial:** dealer transport, fleet management, rental car, auction vehicle, OEM, commercial vehicle, construction equipment, government vehicle

**Buying & Selling:** online car purchase, eBay Motors, Carvana, Copart, IAAI, Bring a Trailer

**Specialty Logistics:** heavy hauling, oversize load, multi-vehicle, hot shot, flatbed, freight, white glove delivery

### Blog (10)
April 5 — May 10, 2026. Cost guides, preparation, comparisons, snowbird, military PCS, online buying, college shipping, scam avoidance.

## Placeholders to Replace Before Launch

- **Phone `(888) 123-4567`** — search & replace across all files
- **Email `info@heartlandautotransport.com`** — same
- **"Get Instant Pricing" buttons** have `href="#"` — replace with real quote tool URL
- **Contact form** — needs a backend handler (Formspree, Netlify Forms, etc.)
