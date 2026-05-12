# Heartland Auto Transport — Complete Website

Alabama-based auto transport company website. Static HTML, ready to deploy.

## Site Stats

- **40 total pages** — 1 homepage + 5 top-level pages + 24 service pages + 10 blog posts
- **All pages SEO-optimized** with unique titles, meta descriptions, schema markup
- **40,000+ words of original content** across the entire site
- **One shared `styles.css`** — edit once, applies everywhere
- **Mobile responsive**, fast-loading static HTML

## Top-Level Pages

| Page | Words | Purpose |
|------|-------|---------|
| `index.html` | Homepage | Hero, services, vehicles, coverage, FAQ |
| `how-it-works.html` | 1,184 | 5-step process, why-Heartland, sub-FAQs |
| `about.html` | 1,265 | Story, Alabama focus, values, credentials |
| `faq.html` | 1,891 | 6-category FAQ with 30+ questions |
| `contact.html` | 506 | Form, 3 contact methods, AL cities grid |
| `blog.html` | Index | All 10 blog post cards |

## 10 Blog Posts (April–May 2026)

| Date | Title | Category | Words |
|------|-------|----------|-------|
| May 10 | How Much Does Auto Transport Cost in 2026? | Cost Guide | 1,082 |
| May 8 | How to Prepare Your Car for Shipping: 10 Steps | Preparation | 1,015 |
| May 5 | Open vs. Enclosed Auto Transport | Comparison | 998 |
| May 2 | Snowbird Car Shipping: AL to FL/AZ/TX | Snowbird Tips | 896 |
| Apr 28 | Shipping a Car Bought Online (Carvana/Vroom/eBay) | Buying Online | 1,135 |
| Apr 25 | Military PCS Auto Transport Guide | Military | 1,029 |
| Apr 22 | Cost to Ship a Car Cross-Country | Cost Guide | 702 |
| Apr 18 | Door-to-Door vs Terminal-to-Terminal | Comparison | 829 |
| Apr 12 | Shipping a Car to College: Parent's Guide | Family | 1,055 |
| Apr 5 | 10 Auto Transport Scams to Avoid in 2026 | Consumer Tips | 1,495 |

## 24 Service Pages

**9 Shipping Methods:** open, enclosed, door-to-door, expedited, cross-country, state-to-state, nationwide, terminal-to-terminal, guaranteed-pickup

**15 Vehicle Types:** car, SUV, truck, motorcycle, EV, luxury, exotic, classic, antique, RV, boat, ATV/UTV, golf cart, van, heavy equipment

## SEO Setup (every page)

- Unique `<title>` and meta description with target keyword
- Canonical URL
- Open Graph + Twitter Card meta tags
- Schema markup:
  - Service pages: Service + FAQPage + BreadcrumbList
  - Blog posts: BlogPosting + BreadcrumbList
  - All pages: geo-targeting for Alabama (US-AL)
- Proper semantic HTML (one H1, hierarchical H2/H3)
- Internal linking between related pages

## Deploy to Cloudflare Pages (Recommended)

1. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** tab → **Upload assets**
2. Project name: `heartlandautotransport` → URL becomes heartlandautotransport.pages.dev
3. Drag the contents of this folder into the upload area
4. Click Deploy site

**After deployment:**
1. Submit `sitemap.xml` to Google Search Console: https://search.google.com/search-console
2. Set up Google Business Profile for local SEO
3. Set up Yelp business page

## Customizing

- **CSS changes** — edit `styles.css`, applies to all 40 pages instantly
- **Replace a photo** — drop a new file in `images/` with the same filename
- **Edit text** — open the relevant `.html` file in any text editor

## Placeholders to Replace Before Launch

- **Phone number `(888) 123-4567`** — search & replace across all files with your real number
- **Email `info@heartlandautotransport.com`** — same
- **"Get Instant Pricing" button** has `href="#"` — swap with your real quote tool URL when ready
- **USDOT/MC number** — currently shown as just "FMCSA Licensed Broker"; append your actual number if desired
- **Contact form action** — the form on contact.html needs a backend handler (Formspree, Netlify Forms, or similar) to actually send emails

## SEO Strategy Summary

**40 pages = 40 ranking opportunities in Google.** Each targets different keywords:

- **Service pages** rank for shipping method/vehicle type searches ("open auto transport", "ship my motorcycle")
- **Blog posts** rank for informational searches ("how much does auto transport cost", "PCS car shipping") capturing top-of-funnel traffic
- **Top-level pages** capture branded searches and rank for trust signals

All content is unique per page (no duplicate content penalty). FAQ and BlogPosting schema across the site means dozens of opportunities for Google rich-snippet displays in search results.
