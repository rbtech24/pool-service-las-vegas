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

## Deploy (Vercel) + Resend contact form

1. Import this repo in Vercel (Framework: **Other**, no build command).
2. Add environment variables:
   - `RESEND_API_KEY` — from [resend.com/api-keys](https://resend.com/api-keys)
   - `EMAIL_FROM` — verified sender, e.g. `Pool Service Las Vegas <onboarding@resend.dev>`
   - `CONTACT_TO` — inbox for leads, e.g. `hello@poolservicelasvegas.com`
3. Deploy. Contact form posts to `/api/contact`.
4. For production, verify your domain in Resend and set `EMAIL_FROM` to that domain (not `onboarding@resend.dev`).

## SEO

- `robots.txt` + `sitemap.xml` at site root
- Canonical, Open Graph, Twitter cards, and JSON-LD on every page
- Blog posts use `BlogPosting` schema; services use `Service` + business schema
