---
type: hub
name: Slide & Poster Design — Reference Hub
description: Index for the design reference. Links the live HTML gallery and the deep-dive guide, with a one-screen cheat sheet for slides, posters, and flyers.
tags: [design, slides, posters, moc, reference]
created: 2026-06-08
---

# 🎨 Slide & Poster Design — Reference Hub

A field guide to how people design slides, posters, and flyers right now. Three pieces:

| Piece | What it's for | Open |
|---|---|---|
| **Live gallery** | See every style as a working mini-slide demo, copy color hexes, browse layouts and fonts | [[Design Styles Gallery.html]] |
| **Full Guide** | The words version: descriptions, hex codes, fonts, step-by-step how-to | [[Slide & Poster Design — Full Guide]] |
| **This hub** | The one-screen cheat sheet and index | you're here |

> [!tip] Start here
> Open **[[Design Styles Gallery.html]]** in a browser (double-click it in the file explorer). Every card is a real recreation of that style, the swatches copy on click, and each card links to live examples.

![[gallery_hero.png]]

---

## The one idea for 2026
> [!abstract] Humanity as a signal
> Most rising styles are a reaction against AI sameness. Raw, hand-made looks (neubrutalism, anti-design, Y2K, kinetic type, "imperfect by design") are surging because they read as made by a person. The hyper-smooth AI-gradient look now signals low effort. On the polished side, three things settled in as the safe modern defaults: **bento grids, dark mode, aurora gradients**. Draft with AI, then rough it up with grain, real photos, and human type choices.

## Styles at a glance
| Rising | Stable staples | Fading / sparingly |
|---|---|---|
| Bento grid · Dark mode · Aurora gradient · Neubrutalism · Anti-design · Kinetic type · Maximalism · Neo-skeuomorphism · 3D/spatial | Glassmorphism · Swiss/editorial · Claymorphism · Organic shapes · Assertive minimalism | Y2K/retro · pure flat design · un-retouched AI gradients |

Full descriptions with colors and best-use: [[Slide & Poster Design — Full Guide#1. Design styles & aesthetics|Full Guide → Design styles]].

## Color quick-picks
> [!info] The 2026 move
> One earthy/organic tone + one sharp digital accent. Warm darks beat pure black (`#0F172A`, `#1C1917`); warm off-whites beat pure white (`#F0EEE9`). Keep the accent to ~10% of the page.

- **Dark SaaS:** `#0F172A` · `#1E293B` · `#E2E8F0` · `#38BDF8`
- **Warm neutral:** `#F5F1E8` · `#A47864` · `#8A9A5B` · `#3A2E27`
- **Navy + accent:** `#1B2A4A` · `#2E4372` · `#F4F6FB` · `#FF7A45`
- **Pantone:** 2025 Mocha Mousse `#A47864` · 2026 Cloud Dancer `#F0EEE9`
- **Colorblind-safe (Okabe-Ito):** `#E69F00 #56B4E9 #009E73 #F0E442 #0072B2 #D55E00 #CC79A7`

All palettes + gradients + accessibility: [[Slide & Poster Design — Full Guide#2. Color|Full Guide → Color]].

## Type quick-picks
- **Free and premium:** Inter, Geist, Space Grotesk, Satoshi, Clash Display, Fraunces, Bricolage Grotesque, JetBrains Mono.
- **Safe pairings:** Fraunces / Inter · Space Grotesk / Inter · Clash Display / General Sans · DM Serif Display / DM Sans.
- **Rules:** two families, three weights max. Slide body 24–32pt, titles 80pt+. Line length 50–75 characters.

Specimens + scale: [[Slide & Poster Design — Full Guide#3. Typography|Full Guide → Typography]].

## Layout patterns
Bento · full-bleed image · big number · split 50/50 · pull-quote · section divider · grid of cards · comparison · title + kicker · timeline. One message per slide; place key content where the eye lands first (Z for sparse, F for dense). Wireframes in the gallery; detail in [[Slide & Poster Design — Full Guide#4. Layout & grid|Full Guide → Layout]].

## Build paths
- **PowerPoint:** Slide Master, theme colors, Morph (`!!` naming trick), Designer, assertion-evidence. → [[Slide & Poster Design — Full Guide#5. Make it: PowerPoint & decks|how-to]]
- **HTML/CSS:** Slidev (dev favorite), reveal.js (standard), Marp (best PPTX export). → [[Slide & Poster Design — Full Guide#6. Make it: HTML/CSS slides|how-to]]
- **Posters/flyers:** Better Poster format, A0 sizing, LaTeX/Canva/Affinity. → [[Slide & Poster Design — Full Guide#7. Posters & flyers|how-to]]

> [!example] For your conference posters (IDETC, ASME)
> Consider the **Better Poster** billboard format: one giant plain-language finding in the center, narrow sidebars for method and limitations, a QR code to the paper, and a short summary bar. Keep body text ≥24pt and let figures dominate (~40% figures, 40% whitespace, 20% text). Check the venue rules first; some judges still expect the traditional column layout. Templates: `osf.io/ef53g`.

---

## File map
- `Design Reference/Design Styles Gallery.html` — the live gallery
- `Design Reference/Slide & Poster Design — Full Guide.md` — the deep dive
- `Design Reference/assets/` — `gallery_full.png` (whole page), `gallery_hero.png` (top)
- `Design Reference/_render_gallery.ps1` — re-renders the screenshots if you edit the HTML

> [!note] Re-rendering
> If you edit the gallery HTML, refresh the screenshots by running `_render_gallery.ps1` (Edge headless). The embed above will update.
