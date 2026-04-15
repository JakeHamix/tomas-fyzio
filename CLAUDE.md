# Fyzioterapie v Ostrově

Single-file landing page for a Czech physiotherapy & wellness retreat.

## Source of truth

All business context, pricing, services, and design decisions are documented in [PRD.md](PRD.md).

## Key rules

- **100% Czech** — no English anywhere on the page (including alt text, aria labels, comments visible to users)
- **Single file** — everything lives in `index.html` (Tailwind via CDN, inline JS, no build step)
- **Dark mode by default** — light mode available via toggle; respect `prefers-color-scheme`
- **Czech typography** — use `&nbsp;` after single-letter prepositions (v, s, z, u, o, k)
- **No booking system** — all CTAs go to WhatsApp/phone/email
- **Target demographic is 40+** — keep typography large and readable

## Tech stack

- Tailwind CSS (CDN)
- Google Fonts: Playfair Display (headings) + Inter (body)
- Lucide Icons (CDN)
- Intersection Observer for scroll animations
- Hosted on GitHub Pages from `main` branch

## Deployment

Push to `main` → GitHub Pages auto-deploys to https://jakehamix.github.io/tomas-fyzio/
