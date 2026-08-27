# Electrical Contractor Kentucky — Landing Page

A single-page SEO landing page targeting the keyword **"electrical contractor Kentucky"**, built as a static site (no build step required).

## Files

| File | Purpose |
|---|---|
| `index.html` | Main landing page. Semantic HTML5 (`header`, `main`, `article`, `section`, `aside`, `footer`), 1000+ word SEO article, on-page meta tags, Open Graph tags, and `Electrician` JSON-LD schema. |
| `robots.txt` | Allows all crawlers and points to the sitemap. |
| `sitemap.xml` | XML sitemap listing the page for search engine submission. |
| `README.md` | This file. |

## Before you go live — replace these placeholders

1. **Domain** — swap every instance of `https://www.yourelectricalcontractorky.com/` (in `index.html`, `robots.txt`, `sitemap.xml`) with your real domain.
2. **Phone number** — replace `(000) 000-0000` and the `tel:+10000000000` links with your real business number.
3. **Business address / city** — update the `address` block in the JSON-LD schema (`index.html`, near the top) with your real city and business details.
4. **Service area cities** — the city chip list under "Areas We Proudly Serve" is a starting set; edit to match the towns you actually service.
5. **OG image** — the `og:image` reference points to `/og-image.jpg`, which doesn't exist yet. Add a real 1200×630 image at that path (or update the tag) for better link-preview thumbnails on social/WhatsApp shares.

## SEO notes

- **Target keyword**: "electrical contractor Kentucky" — used in the title tag, meta description, H1, and naturally throughout the article body.
- **Anchor text**: "electrician services Kentucky" appears exactly once, in the second paragraph of the article, linking out to `https://emergencyelectriciankentucky.com/`. No other links point to that URL anywhere on the page — this was a specific requirement and has been double-checked.
- **Heading structure**: one `H1`, multiple `H2` section headings (Residential, Commercial, Emergency, Panel Upgrades, Why Hire Us, Service Areas, FAQ), with `H3` sub-headings inside the Emergency and Panel Upgrade sections.
- **Images**: the hero illustration and section icons are inline SVG (no external image requests, so nothing to break or slow the page down). Swap them for real photos of your crew/vehicles/jobs whenever you have some — that generally helps local SEO and trust more than illustrations.

## Deploying

This is a static site — no build process. You can:
- Drag the folder into any static host (Netlify, Vercel, GitHub Pages, Cloudflare Pages), or
- Upload the four files via FTP/cPanel to your existing hosting root.

Update `sitemap.xml`'s `<lastmod>` date whenever you make meaningful content changes, and resubmit the sitemap in Google Search Console after the first deploy.
