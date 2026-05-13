# Heartland Auto Transport — Complete Website

Alabama-based auto transport company website. Static HTML, ready to deploy. Fully SEO-optimized and mobile-responsive.

## Site Stats

- **85 HTML pages** — 1 homepage + 5 utility + 24 city + 45 service + 10 blog posts
- **110,000+ words** of original SEO content
- **100% SEO compliance** — every page audited for proper title length, meta description, canonical URL, OG tags, Twitter Card, schema markup, H1, and viewport
- **Fully mobile responsive** — functional hamburger menu, single-column mobile layouts, touch-optimized buttons, 21 responsive breakpoints

## SEO Setup (every page)

✅ Title tag (30-70 chars, optimal for Google search results)
✅ Meta description (70-160 chars, won't get truncated)
✅ Meta keywords
✅ Canonical URL
✅ Viewport meta (mobile responsiveness)
✅ Geo targeting (US-AL)
✅ Open Graph tags (Facebook, LinkedIn previews)
✅ Twitter Card tags (Twitter previews)
✅ Schema.org structured data (rich snippets in Google)
✅ Semantic HTML with single H1 per page
✅ Internal linking between related pages
✅ All images have alt attributes
✅ No broken internal links

## Mobile Setup (every page)

✅ Viewport meta tag with proper scaling
✅ Functional hamburger menu with JS toggle
✅ Animated hamburger → X icon transition
✅ Single-column mobile layouts for all grids
✅ Responsive font sizing (clamp() functions)
✅ Touch-friendly tap targets
✅ Phone number adapts (icon-only on smallest screens)
✅ CTA buttons full-width on mobile
✅ 21 media query breakpoints (1024px, 900px, 880px, 720px, 640px, 560px, 500px, 480px)

## Folder Structure

```
heartland-site/
├── index.html                  ← Homepage
├── how-it-works.html
├── about.html
├── faq.html
├── contact.html
├── blog.html
├── styles.css                  ← Shared stylesheet
├── sitemap.xml                 ← 85 URLs for Google Search Console
├── robots.txt
├── README.md
│
├── cities/                     ← 24 Alabama city pages (Birmingham, Huntsville, etc.)
├── services/                   ← 45 service pages
├── blog/                       ← 10 blog posts
└── images/                     ← 7 images
```

## 45 Service Pages

**Standard Methods (9):** open, enclosed, door-to-door, expedited, cross-country, state-to-state, nationwide, terminal-to-terminal, guaranteed-pickup

**Vehicle Types (15):** car, SUV, truck, motorcycle, EV, luxury, exotic, classic, antique, RV, boat, ATV/UTV, golf cart, van, heavy equipment

**Business & Commercial (8):** dealer transport, fleet management, rental car, auction vehicle, OEM, commercial vehicle, construction equipment, government vehicle

**Buying & Selling (6):** online car purchase, eBay Motors, Carvana, Copart, IAAI, Bring a Trailer

**Specialty Logistics (7):** heavy hauling, oversize load, multi-vehicle, hot shot, flatbed, freight shipping, white glove delivery

## 24 Alabama City Pages

Every Alabama city with 25,000+ population. Each 1,500-2,200 words of unique, locally-relevant content. Top cities: Huntsville (222k), Mobile (203k), Birmingham (198k), Montgomery (197k), Tuscaloosa (111k), Hoover (92k), Auburn (80k), Dothan (71k), Madison (60k), Decatur (57k) — plus 14 more.

## 10 Blog Posts (April–May 2026)

Cost guides, preparation, comparisons, snowbird, online buying, military PCS, scams to avoid, college shipping, and more.

## Deploy to Cloudflare Pages

1. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** tab → **Upload assets**
2. Project name: `heartlandautotransport`
3. Drag the contents of this folder into the upload area
4. Click Deploy site

After deployment:
1. Submit `sitemap.xml` (85 URLs) to Google Search Console: https://search.google.com/search-console
2. Set up Google Business Profile for local SEO
3. Set up Yelp business page

## Customizing

- **CSS changes** — edit `styles.css`, applies to all 85 pages instantly
- **Replace a photo** — drop a new file in `images/` with the same filename
- **Edit text** — open any `.html` file in a text editor

## Placeholders to Replace Before Launch

- **Phone `(888) 123-4567`** — search & replace across all files with your real number
- **Email `info@heartlandautotransport.com`** — same
- **"Get Instant Pricing" buttons** have `href="#"` — swap with your real quote tool URL
- **USDOT/MC number** — currently shown as just "FMCSA Licensed Broker"
- **Contact form** — needs a backend handler (Formspree, Netlify Forms, etc.)
