# Heartland Auto Transport — Complete Website

Alabama-based auto transport company website. Static HTML, ready to deploy.

## Site Stats

- **85 total HTML pages** — 1 homepage + 5 utility + 24 Alabama city pages + 45 service pages + 10 blog posts
- **110,000+ words of original SEO content**
- All pages SEO-optimized with unique titles, meta descriptions, schema markup
- Mobile responsive, fast-loading static HTML
- One shared `styles.css` for the entire site

## Folder Structure

```
heartland-site/
├── index.html                  ← Homepage
├── how-it-works.html
├── about.html
├── faq.html
├── contact.html
├── blog.html
├── styles.css
├── sitemap.xml                 ← 85 URLs for Google Search Console
├── robots.txt
├── README.md
│
├── cities/                     ← 24 Alabama city pages
├── services/                   ← 45 service pages
├── blog/                       ← 10 blog posts
└── images/                     ← 7 images
```

## 45 Service Pages — Categorized

### Standard Shipping Methods (9)
- Open Auto Transport
- Enclosed Auto Transport
- Door-to-Door
- Expedited Auto Transport
- Cross Country
- State-to-State
- Nationwide Auto Transport
- Terminal-to-Terminal
- Guaranteed Pickup

### Vehicle Types (15)
- Car Shipping, SUV Transport, Truck Shipping, Motorcycle Shipping, Electric Vehicle Shipping, Luxury Car Transport, Exotic Car Transport, Classic Car Transport, Antique Vehicle Shipping, RV Transport, Boat Transport, ATV/UTV Shipping, Golf Cart Shipping, Van Transport, Heavy Equipment Transport

### Business & Commercial (8) — NEW
- Dealer Auto Transport
- Fleet Management Transport
- Rental Car Transport
- Auction Vehicle Transport
- OEM Vehicle Shipping
- Commercial Vehicle Shipping
- Construction Equipment Shipping
- Government Vehicle Transport

### Buying & Selling (6) — NEW
- Online Car Purchase Shipping
- Car Shipping for eBay Motors
- Carvana Vehicle Transport
- Copart Auto Transport
- IAAI Vehicle Shipping
- Bring a Trailer Shipping

### Specialty Logistics (7) — NEW
- Heavy Hauling
- Oversize Load Transport
- Multi Vehicle Transport
- Hot Shot Transport
- Flatbed Transport
- Freight Shipping
- White Glove Vehicle Delivery

## 24 Alabama City Pages (in /cities/)

Every Alabama city with 25,000+ population. Each is 1,500-2,200 words of unique, locally-relevant content covering local routes, neighborhoods, industries, and shipping demand drivers.

URL pattern: `/cities/{city}-auto-transport.html`

Top cities: Huntsville (222k), Mobile (203k), Birmingham (198k), Montgomery (197k), Tuscaloosa (111k), Hoover (92k), Auburn (80k), Dothan (71k), Madison (60k), Decatur (57k) — plus 14 more cities.

## 10 Blog Posts (in /blog/)

April 5 → May 10, 2026. Categories: Cost Guide, Preparation, Comparison, Snowbird, Online Buying, Military, Family, Consumer Tips.

## SEO Strategy

**85 pages = 85 ranking opportunities in Google.**

The new commercial/business service pages target high-value B2B searches:
- "dealer auto transport"
- "fleet management transport"
- "Copart vehicle pickup"
- "Carvana shipping alternative"
- "heavy hauling Alabama"
- "white glove vehicle delivery"

These are HIGH-INTENT searches from dealers, fleet managers, businesses, and specialty buyers — typically much higher conversion value than consumer searches.

Every page includes:
- Service + BreadcrumbList schema markup
- Geo-targeting meta tags (US-AL)
- Unique title, meta description, keywords
- Internal links to related services
- Open Graph + Twitter Card meta tags
- 800-2,200 words of unique, original content

## Deploy to Cloudflare Pages

1. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** tab → **Upload assets**
2. Project name: `heartlandautotransport`
3. Drag the contents of this folder into the upload area
4. Click Deploy site

**After deployment:**
1. Submit `sitemap.xml` (85 URLs) to Google Search Console
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
