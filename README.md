# Pool Service Las Vegas

Static local SEO site for **Las Vegas, NV**.

## Pages
- Home, Services (6 detail pages), Service Areas, Pricing, About, FAQ, Contact
- Blog index + 8 local articles
- Unique mobile app bar (`neon` style)

## Before launch
1. Replace demo phone `(702) 555-0180` with real NAP
2. Set real email / domain references
3. Connect contact form to backend
4. Add Google Business Profile Place ID (no fake review schema)
5. Deploy folder to Netlify, Cloudflare Pages, or any static host

## Design theme
`vegas` — fonts and mobile app bar are exclusive to this brand.

## Deploy (Vercel)

Static site. Framework: **Other**, no build. Phone CTAs use `tel:` links — no form backend required.


## SEO

- `robots.txt` + `sitemap.xml` at site root
- Canonical, Open Graph, Twitter cards, and JSON-LD on every page
- Blog posts use `BlogPosting` schema; services use `Service` + business schema
