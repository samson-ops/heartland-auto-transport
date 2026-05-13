# Heartland Auto Transport — Complete Website

Alabama-based auto transport company website. Static HTML, ready to deploy.

## Site Stats

- **64 total HTML pages** — 1 homepage + 5 utility + 24 Alabama city pages + 24 service pages + 10 blog posts
- **90,000+ words of original SEO content**
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
├── styles.css                  ← Shared stylesheet
├── sitemap.xml                 ← 64 URLs for Google Search Console
├── robots.txt
├── README.md
│
├── cities/                     ← 24 Alabama city pages
│   ├── birmingham-auto-transport.html
│   ├── huntsville-auto-transport.html
│   ├── mobile-auto-transport.html
│   └── ... (21 more cities)
│
├── services/                   ← 24 service pages
│   ├── open-auto-transport.html
│   ├── enclosed-auto-transport.html
│   └── ... (22 more services)
│
├── blog/                       ← 10 blog posts
│   ├── how-much-does-auto-transport-cost.html
│   └── ... (9 more posts)
│
└── images/                     ← 7 images
    ├── logo.png
    ├── hero-truck.jpg
    └── ...
```

## 24 Alabama City Pages (in /cities/)

Every Alabama city with 25,000+ population. Each page is 1,500-2,200 words of unique, locally-relevant content.

URL pattern: `/cities/{city}-auto-transport.html`

| Rank | City | Population | Words |
|------|------|-----------|-------|
| 1 | Huntsville | 222,791 | 2,186 |
| 2 | Mobile | 203,416 | 2,183 |
| 3 | Birmingham | 198,173 | 2,193 |
| 4 | Montgomery | 197,494 | 2,201 |
| 5 | Tuscaloosa | 111,038 | 2,185 |
| 6 | Hoover | 92,642 | 2,190 |
| 7 | Auburn | 80,594 | 2,195 |
| 8 | Dothan | 71,514 | 2,203 |
| 9 | Madison | 60,106 | 2,206 |
| 10 | Decatur | 57,361 | 2,204 |
| 11 | Florence | 41,701 | 2,204 |
| 12 | Prattville | 39,482 | 2,180 |
| 13 | Vestavia Hills | 38,616 | 2,264 |
| 14 | Phenix City | 38,499 | 2,276 |
| 15 | Alabaster | 33,917 | 2,149 |
| 16 | Gadsden | 33,374 | 2,183 |
| 17 | Opelika | 32,820 | 2,162 |
| 18 | Northport | 31,218 | 2,197 |
| 19 | Enterprise | 29,505 | 2,223 |
| 20 | Daphne | 29,453 | 2,199 |
| 21 | Athens | 29,002 | 2,189 |
| 22 | Homewood | 27,829 | 2,176 |
| 23 | Trussville | 26,673 | 2,183 |
| 24 | Bessemer | 25,400 | 2,170 |

Every city has unique content tied to local industries:
- **Huntsville** — aerospace, Redstone Arsenal, defense contractor routes
- **Mobile** — Port of Mobile, Airbus, Austal shipbuilding
- **Birmingham** — UAB Hospital, Regions Bank, healthcare/finance
- **Auburn** — Auburn University SEC college shipping
- **Enterprise** — Fort Novosel military PCS
- **Daphne** — Eastern Shore snowbird community
- **Athens** — Toyota Mazda manufacturing plant
- ...and so on for every city

## How to Find the City Pages

**From the homepage:** Scroll down to "Auto Transport Service Areas in Alabama" — every city has a clickable tile.

**Direct URLs (once deployed):**
- `heartlandautotransport.com/cities/birmingham-auto-transport.html`
- `heartlandautotransport.com/cities/huntsville-auto-transport.html`
- etc.

## 10 Blog Posts (in /blog/)

April 5 → May 10, 2026. Categories: Cost Guide, Preparation, Comparison, Snowbird, Online Buying, Military, Family, Consumer Tips.

## 24 Service Pages (in /services/)

**9 Shipping Methods:** open, enclosed, door-to-door, expedited, cross-country, state-to-state, nationwide, terminal-to-terminal, guaranteed-pickup

**15 Vehicle Types:** car, SUV, truck, motorcycle, EV, luxury, exotic, classic, antique, RV, boat, ATV/UTV, golf cart, van, heavy equipment

## SEO Strategy

**64 pages = 64 ranking opportunities in Google.**

City pages target local searches like:
- "auto transport Birmingham AL"
- "car shipping Huntsville Alabama"
- "Mobile AL auto transport service"
- "ship car from Auburn Alabama"

These are HIGH-INTENT local searches with strong commercial conversion. Google ranks local pages with city-specific content well — especially when paired with structured data (which every page includes).

Every city page includes:
- Service + FAQPage + BreadcrumbList schema markup
- Geo-targeting meta tags (US-AL, specific city)
- Unique title, meta description, keywords
- Internal links to relevant service pages
- Open Graph + Twitter Card meta tags

## Deploy to Cloudflare Pages

1. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** tab → **Upload assets**
2. Project name: `heartlandautotransport`
3. Drag the contents of this folder into the upload area (drag the contents, not the folder itself)
4. Click Deploy site

Your site goes live at `heartlandautotransport.pages.dev`.

**After deployment:**
1. Submit `sitemap.xml` (64 URLs) to Google Search Console
2. Set up Google Business Profile for local SEO
3. Set up Yelp business page

## Customizing

- **CSS changes** — edit `styles.css`, applies to all 64 pages instantly
- **Replace a photo** — drop a new file in `images/` with the same filename
- **Edit text** — open any `.html` file in a text editor

## Placeholders to Replace Before Launch

- **Phone `(888) 123-4567`** — search & replace across all files with your real number
- **Email `info@heartlandautotransport.com`** — same
- **"Get Instant Pricing" buttons** have `href="#"` — swap with your real quote tool URL
- **USDOT/MC number** — currently shown as just "FMCSA Licensed Broker"; append your actual number if desired
- **Contact form action** — the form on contact.html needs a backend handler (Formspree, Netlify Forms, etc.) to actually send emails
