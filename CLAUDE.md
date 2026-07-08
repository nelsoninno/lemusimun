# Lemusimún — site notes (everybodyknowsyou.com managed)

- **Live:** https://lemusimun.com (ES at `/`, EN mirror at `/en/`; FAQ at `/faq/` and `/en/faq/`)
- **Repo:** github.com/nelsoninno/lemusimun — branch `main`
- **Hosting:** Cloudflare Pages, auto-deploys on push to `main` (~1 min)
- **Type:** business, bilingual (ES primary, EN mirror). Single-page each, inline CSS.
- **Discoverability:** meta/canonical/hreflang/OG, JSON-LD @graph (Organization + LocalBusiness + WebSite + service OfferCatalog + VideoObject on home; FAQPage on the /faq pages), robots.txt, sitemap.xml, llms.txt + llms-full.txt, favicon stack, og-cover.jpg. No em-dashes.
- **Hero headings:** H1 = "Lemusimún, agencia de publicidad en El Salvador desde 1976" (EN: "...advertising agency in El Salvador since 1976"), rendered as the small eyebrow pill. H2 = the big "Un legado que no se detiene" / "A legacy that never stops" (visually largest, but H2 by design for SEO/GEO).
- **FAQ:** lives on /faq/ and /en/faq/ only, linked from the footer (not the main menu).
- **Rule:** every content edit updates BOTH languages and re-runs the seo-ai-findability section 15 gate. Keep the EKY footer credit.
- **Cloudflare note:** zone-level "Managed robots.txt" currently overrides the repo robots.txt (blocks AI training). Disable it in the dashboard to honor allow-all.

## Change log
- **2026-07-08 (1)** — SEO + AI-findability upgrade: full head, JSON-LD graph, FAQ, robots.txt, sitemap.xml, llms.txt/llms-full.txt, favicon stack, og-cover.jpg; built English /en/ with ES|EN switch; repaired truncated footer + added EKY credit; removed em-dashes.
- **2026-07-08 (2)** — Reverted the hero H1 to the original tagline "Un legado que no se detiene" / "A legacy that never stops" (kept the SEO keyword in title/meta/schema). Eyebrow shows "Lemusimún, desde 1976". Moved the FAQ off the home page to dedicated /faq/ and /en/faq/ pages (with FAQPage JSON-LD), linked only from the footer. Updated sitemap.
- **2026-07-08 (3)** — Hero heading swap: made the keyword line ("Lemusimún, agencia de publicidad en El Salvador desde 1976" / EN "...since 1976") the H1 (the small top eyebrow), and demoted the big "Un legado que no se detiene" / "A legacy that never stops" to H2. Visual layout unchanged; only the semantic tags swapped, for SEO/GEO/AEO.
