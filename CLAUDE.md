# Lemusimún — site notes (everybodyknowsyou.com managed)

- **Live:** https://lemusimun.com (ES at `/`, EN mirror at `/en/`)
- **Repo:** github.com/nelsoninno/lemusimun — branch `main`
- **Hosting:** Cloudflare Pages, auto-deploys on push to `main` (~1 min)
- **Type:** business, bilingual (ES primary, EN mirror). Single-page each, inline CSS.
- **Discoverability:** meta/canonical/hreflang/OG, JSON-LD @graph (Organization + LocalBusiness + WebSite + service OfferCatalog + FAQPage + VideoObject), visible FAQ, robots.txt (allows all crawlers incl. AI + Sitemap; overrides Cloudflare-managed robots), sitemap.xml, llms.txt + llms-full.txt, favicon stack, og-cover.jpg. No em-dashes anywhere.
- **Rule:** every content edit must update BOTH `/` and `/en/` and re-run the seo-ai-findability section 15 gate. Keep the EKY footer credit.

## Change log
- **2026-07-08** — SEO + AI-findability upgrade (EKY-side, website-update). Added the full discoverability layer (head, JSON-LD graph, FAQ, robots.txt, sitemap.xml, llms.txt/llms-full.txt, favicon stack, og-cover.jpg). Built the English version at `/en/` with an ES|EN language switch. New H1: "Lemusimún, agencia de publicidad en El Salvador desde 1976" / EN "Lemusimún, advertising agency in El Salvador since 1976"; moved "Un legado que no se detiene" to the hero eyebrow. Repaired the truncated footer (was cut off mid-tag) and added the copyright line + everybodyknowsyou credit. Removed all em-dashes.
