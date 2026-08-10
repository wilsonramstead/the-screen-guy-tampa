# The Screen Guy of Tampa — Demo Website

A single-page demo site built for **The Screen Guy of Tampa, Inc.**, a pool screen enclosure and lanai re-screening company in Lutz, FL. Part of the Wilson's Websites demo-first pitch workflow (build first, then share the link).

## The business
- **Name:** The Screen Guy of Tampa, Inc.
- **Location:** 406 Duque Rd, Lutz, FL 33548 (serves Lutz & the greater Tampa Bay area)
- **Phone:** (813) 240-2109
- **Hours:** Mon–Fri 7 AM – 7 PM; Sat 9 AM – 5 PM; Sun closed
- **Google:** 4.8 ★ (69 reviews)
- **Owner:** Justin (crew includes installers Kim & Jaye per reviews)
- **Known for:** next-business-day service, quick to respond, meticulous/tidy crew, reasonable up-front pricing, repeat customers
- **Services:** pool screen enclosures / full pool-cage re-screens · panel & lanai re-screening (rolling-spline tool) · aluminum bars & structural rebuilds · screen doors, people-doors & pet/doggie doors, plus repairs

## Design (Tier 1 — Clean Slate)
- **Fonts:** Contrail One (airy display sans) + Noto Serif Georgian (serif body), via Google Fonts — breezy, coastal, trustworthy.
- **Palette:** gulf teal + screen charcoal over lanai white, with a warm sunset-gold accent (from the hero) for stars and the headline highlight.
- **Layout:** sticky header (call CTA flush right, icon-only ≤600px, hamburger mobile nav), full-bleed hero over a sunset screened pool enclosure with a slow Ken Burns settle, charcoal trust strip, four service cards, a "Why Tampa Bay calls The Screen Guy" feature band, a pull-quote, three real Google reviews, hours & service-area block, and a teal CTA band.
- Scroll reveals use the finalized recipe (translateY + scale + blur, .8s ease, IntersectionObserver rootMargin bottom +12%), all gated behind `prefers-reduced-motion`.
- No fixed/sticky bottom mobile call bar (the header call CTA is the persistent contact affordance).
- Hero stack (eyebrow → headline → sub → CTA pair → glass trust chip) verified fully visible with no scroll at 1440×900 and 1366×768.

## Image credits (Unsplash placeholder stock — swap in real job photos after sale)
All IDs verified HTTP 200 and de-duplicated against every existing site (`websites/*/index.html` + `websites/*/README.md`) and `templates/*/` immediately before download. Every image visually confirmed to match its alt text.

- `hero.jpg` / `og-preview.jpg` — screened pool enclosure at sunset with a travertine deck, lounge chairs, pool and palms (the actual product): `photo-1656443876192-22c578744a04`
- `svc-enclosure.jpg` — screened pool cage over a pool and spa in dark aluminum: `photo-1618868460433-bd99af641e47`
- `svc-rescreen.jpg` — screen enclosure panels beside a pool and palm trees: `photo-1653322462057-b791bd8badeb`
- `svc-aluminum.jpg` — bare aluminum screen-enclosure frame against a bright blue sky with palms: `photo-1724248309705-7503a99e8c85`
- `svc-lanai.jpg` — bright white screened lanai/porch with lounge chairs under a blue sky: `photo-1781921131519-8830442ea1b6`
- `feature.jpg` — modern Florida home with a swimming pool and palm trees on a travertine deck: `photo-1763479142525-1a3b1f7800c2`

## Notes / conventions
- `noindex, nofollow` is set while this is a demo — remove the robots meta (see the `<!-- DEMO -->` comment in `<head>`) when the site goes live.
- Open Graph and Twitter Card tags use absolute URLs at `https://wilsoninnovations.net/the-screen-guy-tampa/` for correct link previews.
- HomeAndConstructionBusiness / LocalBusiness JSON-LD structured data included.
- No contact forms, no fixed bottom call bar. No invented facts (no prices, emails, license numbers, or founding years). Rating shown (4.8 ≥ 4.4). Reviews are real Google reviews, attributed by first name + last initial.
- Confirm the best contact number on the call before going live.

## Deploy
Static single file — `index.html` + `assets/`. Hosted via GitHub Pages at:
**https://wilsoninnovations.net/the-screen-guy-tampa/**

---
Website by [Wilson Innovations](https://wilsoninnovations.net).
