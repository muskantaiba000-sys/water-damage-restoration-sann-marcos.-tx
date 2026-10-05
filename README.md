# Water Damage Restoration San Marcos TX

Professional website for Rapid Response Restoration San Marcos, a water damage restoration company serving San Marcos, TX and the surrounding area.

## Structure

- `index.html` — Homepage
- `about.html` — About page
- `contact.html` — Contact page
- `services.html` — Services overview
- `locations.html` — Service areas overview
- `privacy-policy.html` — Privacy policy
- `404.html` — Custom not-found page
- `services/` — 10 individual service pages (emergency water extraction, structural drying, flood damage cleanup, storm damage restoration, mold remediation, sewage cleanup, burst & frozen pipe, ceiling & roof leak, appliance leak cleanup, inspection & moisture detection)
- `locations/` — 5 individual location pages (San Marcos, Kyle, Buda, New Braunfels, Wimberley)

## Assets

- `assets/global.css` — Custom CSS variables/theme (colors, radius) and base styles; pages also load Tailwind CSS via the `@tailwindcss/browser` CDN script for utility classes
- `assets/js/main.js` — Site JavaScript (FAQ/legacy code removed; the mobile nav toggle is inline in each page)
- `assets/images/` — Photos, logo, and favicon
- `assets/archive/unused/` — Assets kept for reference but not currently referenced by any page (do not delete without checking)

## Configuration & SEO

- `business-info.json` — Social links, address, footer link data
- `robots.txt` — Crawler directives (allows all, points to sitemap)
- `sitemap.xml` — Full list of indexable URLs
- `.htaccess` — Clean-URL rewrites and caching rules for Apache/LiteSpeed hosts (cPanel, SiteGround, etc.)
- `_redirects` — Clean-URL redirects for Netlify
- `netlify.toml` — Netlify build config (pretty URLs)
- `vercel.json` — Clean-URL redirects and settings for Vercel
- Each page includes JSON-LD structured data (LocalBusiness, AdministrativeArea, FAQPage, BreadcrumbList as applicable) and Open Graph tags

## Setup Instructions

1. Upload all files to your web hosting provider, preserving the folder structure (`services/`, `locations/`, `assets/`).
2. Netlify/Vercel: `_redirects`/`vercel.json` + `netlify.toml` handle clean URLs automatically. Apache/cPanel hosts: `.htaccess` handles it instead.
3. Test navigation, forms, and phone/CTA links after deploying.
4. Update `business-info.json` and canonical/OG URLs if the domain changes.

## Features

- Responsive design
- SEO optimized (titles, meta descriptions, canonical tags, structured data, sitemap)
- Dynamic service and location pages for local SEO
- Mobile-friendly navigation (inline slide-out sidebar per page)
- Emergency phone CTA bar

Generated with Ranklocal - Professional website creation tool.
