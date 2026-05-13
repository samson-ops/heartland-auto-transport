# Heartland Auto Transport — Complete Website

Alabama-based auto transport company website. Production-ready static site.

## What's Inside (45 pages)

### Core Pages (6)
- `index.html` — Homepage with hero, services, coverage, FAQ
- `how-it-works.html` — Step-by-step process page (HowTo schema)
- `about.html` — Company story, values, Alabama roots
- `faq.html` — Comprehensive FAQ across 6 categories (FAQPage schema)
- `contact.html` — Contact form, phone, email, service areas (ContactPage schema)
- `blog.html` — Blog landing page

### Service Pages (24) — in `/services/`
**9 Shipping Methods:**
- open-auto-transport, enclosed-auto-transport, door-to-door-auto-transport
- expedited-auto-transport, cross-country-car-shipping, state-to-state-car-shipping
- nationwide-auto-transport, terminal-to-terminal-shipping, guaranteed-pickup-services

**15 Vehicle Types:**
- car-shipping, suv-transport, truck-shipping, motorcycle-shipping
- electric-vehicle-shipping, luxury-car-transport, exotic-car-transport
- classic-car-transport, antique-vehicle-shipping, rv-transport, boat-transport
- atv-utv-shipping, golf-cart-shipping, van-transport, heavy-equipment-transport

### Blog Articles (6) — in `/blog/`
- how-much-does-auto-transport-cost.html (1,369 words)
- how-to-prepare-your-car-for-shipping.html (1,507 words)
- open-vs-enclosed-auto-transport.html (1,130 words)
- snowbird-car-shipping-guide.html (1,108 words)
- shipping-a-car-bought-online.html (1,327 words)
- military-pcs-auto-transport.html (1,098 words)

### Assets
- `styles.css` — Single stylesheet for all pages (~60KB)
- `images/` — Logo, hero, services, map, vehicle photos
- `sitemap.xml` — 36 URLs for Google Search Console
- `robots.txt` — Allows all crawlers

## SEO Features
- Unique title + meta description on every page
- Schema.org markup (LocalBusiness, Service, FAQPage, BlogPosting, HowTo, BreadcrumbList, ContactPage, AboutPage)
- Canonical URLs
- Open Graph + Twitter cards
- Geo-targeting (US-AL)
- Sitemap with priority signals
- Internal linking throughout

## Before Going Live — Replace These Placeholders
1. **Phone number** — Find/replace `(888) 123-4567` and `tel:8881234567`
2. **Email** — Find/replace `info@heartlandautotransport.com`
3. **Quote button URL** — Search for `id="instant-pricing-btn"` and `href="#"` — connect to your quote tool/form processor
4. **Contact form handler** — `contact.html` has placeholder JS `handleContactSubmit()` — connect to Formspree, Netlify Forms, or similar
5. **Privacy Policy / Terms** — Footer links go to `href="#"` — add real pages or remove
6. **USDOT/MC numbers** — Footer says "FMCSA Licensed Broker" — add specific numbers if desired

## Deployment to Cloudflare Pages

1. Go to dash.cloudflare.com → Workers & Pages → Create → Pages → Upload assets
2. Project name: `heartlandautotransport` (gives you heartlandautotransport.pages.dev)
3. Drag the entire `heartland-site` folder contents into the upload area
4. Click Deploy
5. Once live, add your custom domain in the Custom Domains tab
6. Submit `sitemap.xml` to Google Search Console for indexing

## File Count Summary
- 6 core pages
- 24 service pages
- 6 blog articles
- 1 stylesheet
- 7 images
- sitemap.xml + robots.txt
- **Total: 45 HTML pages + assets**

## Tech Stack
- Pure static HTML/CSS — no build process needed
- Single shared stylesheet for fast loading
- Mobile-responsive throughout
- Works on any static host (Cloudflare Pages, Netlify, Vercel, GitHub Pages, S3, etc.)
- No JavaScript dependencies except the contact form placeholder

---
Built for Heartland Auto Transport · Trusted. Reliable. On the Road with Care.
