---
type: reference
name: Slide & Poster Design — Full Guide
description: Deep-dive written companion to the Design Styles Gallery. Styles, color, type, layout, and how to build slides/posters/flyers, current to 2025–2026.
tags: [design, slides, posters, typography, color, reference]
created: 2026-06-08
---

# Slide & Poster Design — Full Guide

> The text companion to **[[Design Styles Gallery.html]]** (open it in a browser for live demos) and **[[Slide & Poster Design — Reference Hub]]** (the Obsidian index). This is the words version: descriptions, hex codes, font names, and step-by-step how-to. Built from a June 2026 sweep of practitioner sources; links and a caveats note are at the bottom.

## How to use this
- **Browsing for a look?** Open the gallery HTML and skim the live cards, then come back here for the detail.
- **Building something?** Jump to [Make it: PowerPoint](#5-make-it-powerpoint--decks), [Make it: HTML/CSS](#6-make-it-htmlcss-slides), or [Posters & flyers](#7-posters--flyers).
- **Picking colors or fonts?** [Color](#2-color) and [Typography](#3-typography) have copy-ready values.

## The one big idea for 2026: humanity as a signal
Almost every rising style this year is a reaction to AI sameness. Raw, hand-made, imperfect looks (neubrutalism, anti-design, Y2K, kinetic type, maximalism, the "imperfect by design" movement) are surging because they read as made by a person. The hyper-smooth AI-generated gradient look is sliding the other way: it now signals low effort. On the polished side, three things settled in as the safe modern defaults: **bento grids, dark mode, and aurora gradients**. The practical takeaway: use AI to draft, then rough it up with grain, real photography, odd crops, and human typographic choices so it doesn't look generated.

---

## 1. Design styles & aesthetics

Each entry: what it is, status for 2026, colors/fonts, and where to use it. The gallery has a live demo for the starred ones.

### Polished / modern defaults

**Bento grid** · *Rising, basically the settled standard.*
Compartmentalized rounded cards of varying sizes, the Apple-lunchbox look. Hierarchy comes from box size: the biggest cell holds the hero idea. Scannable and premium, and it measurably increases scroll depth. Keep it to about six cells. Works in any palette and especially in dark mode. **Best for:** feature showcases, dashboards, capability and summary slides. Used by Apple, Samsung, Microsoft, Google.

**Dark mode / dark-glass** · *Rising.*
A dark-first philosophy rather than an inverted light theme. Use warm near-black bases (#0A0A0F to #121212), express elevation through brightness and subtle light borders, and let desaturated accents glow. Pairs naturally with aurora and glass. **Best for:** dev tools, SaaS, media, evening-use apps, high-tech decks. References: Linear, Vercel.

**Aurora / mesh gradient** · *Rising.*
Large blurred color blobs blended over a dark base, like the northern lights, often gently animated. This is the "living gradient" that replaced flat fills and signals technical sophistication. Build it with layered radial gradients plus background-blend-mode. Pros interpolate ~12 color stops for the alive Stripe/Apple read; amateurs use two. **Best for:** dark backgrounds, title and section slides, SaaS heroes.

**Glassmorphism** · *Stable, matured, needs restraint.*
Frosted translucent panels over color or photography, with a hairline light-catching border and a real backdrop blur. Apple's 2025 "Liquid Glass" gave it fresh credibility, and the backlash came from putting it on everything. Use an alpha-gradient fill (lighter top-left) rather than a flat 50% opacity, a `rgba(255,255,255,0.12)` border, and `backdrop-filter: blur()`. **Best for:** modals, nav, overlays, one or two hero cards. Selective use only.

**Swiss / International / editorial** · *Stable, foundational.*
Grid-driven clarity, "form follows function": a mathematical column grid, flush-left ragged-right type, neutral sans (Helvetica, Neue Haas, Akzidenz), photography over illustration, and generous whitespace. The 2026 twist is sharper high-contrast serifs returning for editorial work, with the type itself acting as the hero image. **Best for:** editorial, news, conference branding, data-heavy decks that need legibility.

**Assertive minimalism** · *Rising.*
Confident restraint with warmth. One idea, strong type, high contrast, and a tactile warm off-white canvas (Pantone's 2026 Cloud Dancer fits). Bolder and more human than the cold flat minimalism of the 2010s. **Best for:** luxury, premium SaaS, editorial, single-message slides.

### Tactile / dimensional

**Claymorphism** · *Stable.*
Puffy, inflated 3D shapes with a soft inner glow and double shadows, plus big friendly icons. A tangible evolution of soft UI. Warm pastels (peach, lilac, mint) and rounded sans (Nunito, Poppins). **Best for:** onboarding, CTAs, feature cards, kids and wellness products. Avoid data-dense pages.

**Neumorphism / soft UI** · *Niche.*
Monochrome elements that look pressed into or extruded from the background using twin light and dark shadows. Beautiful but historically low-contrast; the modern version meets WCAG and stays the native dialect of spatial and AR UI. Base around #E0E5EC. **Best for:** premium single controls, toggles, finance and smart-home dashboards. Avoid dense interfaces.

**Neo-skeuomorphism** · *Rising.* (no gallery demo)
Dimensional material and depth without the literal leather-and-felt metaphors of the 2010s: soft shadows, tactile surfaces, real materiality used selectively on app icons, onboarding, empty states, and Vision Pro UI. Mix flat chrome with dimensional emphasis. **Best for:** marketing pages, app icons, spatial UI, emphasis moments.

**3D & spatial design** · *Rising, driven by Vision Pro and Quest.* (no gallery demo)
Real depth, lighting, and physics; spatial storytelling and AR product previews. Spline and Framer make no-code 3D accessible. Heavy WebGL often underdelivers on performance, so use it with purpose. **Best for:** product launches, AR commerce, immersive heroes, headset UI.

### Raw / expressive / anti-AI

**Neubrutalism** · *Rising.*
Thick black borders, hard zero-blur drop shadows, saturated clashing blocks, rigid grids, and mismatched type. Reads as deliberately human. Vibrant high-saturation hues (#38DBFF, #FFB443, #FF5D5D, #FFF503, #00FF75) on #000000, with Space Grotesk and bold grotesques. **Best for:** creative agencies, dev tools, portfolios, events with attitude. Reference: Gumroad.

**Anti-design** · *Rising.*
Deliberately breaks the rules: asymmetry, clashing type, raw naive layouts, scanned and collaged textures, intentional friction. The "imperfect by design" backlash against AI smoothness. Overlaps neubrutalism. **Best for:** cultural and creative brands, zines, music, statement campaigns.

**Maximalism / dopamine** · *Rising.*
Layered type, color, and texture turned up, with structure underneath so it still reads. Saturated "dopamine" brights as a scroll-stopper. A loud reaction to minimalist sameness. **Best for:** youth, lifestyle, beauty, music, bold campaigns. (Minimalism and maximalism are both rising; 2026 is a pluralistic both/and year.)

**Kinetic / big expressive type** · *Flagship motion trend of 2026.*
Viewport-scale headlines that stretch, build, and morph on scroll or hover, with variable fonts driving weight and width shifts. Type becomes the primary architecture, and because it is lighter than imagery it is also more sustainable. Always respect `prefers-reduced-motion`. **Best for:** hero headlines, brand sites, title and section slides.

**Y2K / retro** · *Stable to fading.*
Chrome type, holographic gradients, pixel fonts, and lo-fi texture from the early-web era. Still a strong anti-AI craft signal, but fatigue is setting in; in 2026 pull a single element rather than the whole throwback. Metallic silver, iridescent purple-blue-pink, lime. **Best for:** music, fashion, Gen-Z youth brands, event flyers. Sparingly.

**Vaporwave / synthwave / retro-futurism** · *Rising.*
Past visions of the future: chrome finishes, muted neon glows, sci-fi typography, perspective grids, and sunsets. Synthwave layers neon over dark for immersive web. The related Frutiger Aero sub-trend is the clean glossy "default future" optimism (water droplets, skies, gloss). Cosmic neon (magenta, cyan, purple) plus metallic gradients. **Best for:** music, gaming, tech launches, immersive experiences.

**Organic / blob shapes** · *Stable to rising.*
Soft irregular shapes, fluid section dividers, and flowing curves used as masks, backgrounds, and gradient carriers. Soothing and human, a calm counter to rigid grids. Soft gradients and pastels with rounded sans. **Best for:** wellness, medical, smart-home, friendly brand sites.

### Contested

**Flat design / Material** · *Evolving.* (no gallery demo)
Flat fills and simple icons. Google's Material 3 Expressive (May 2025) pushes it back toward depth, bold color, shape, and animation, and tested as faster to use. Pure flat is increasingly called incomplete for comprehension. **Best for:** Android apps, large utility systems, dense accessible UI.

**The AI-generated look** · *Fading as an aesthetic, rising as a tool.* (no gallery demo)
Hyper-smooth synthetic gradients and illustration now read as default and cheap. The dominant counter-move is to run AI for raw assets and then break the polish with grain, sketch, collage, odd crops, and real texture. Ship the human pass.

---

## 2. Color

### Pantone Color of the Year
- **2025 — Mocha Mousse**, PANTONE 17-1230, about **#A47864**. A warm grounded brown. Use it as a sophisticated neutral base or large background. It is medium-dark, so it fails AA as body text on white. Pair with cream (#F5F1E8), olive, terracotta, plus one digital accent. (Hex varies by source between #A47864 and #A47764 because Pantone is a proprietary spot system; treat as approximate.)
- **2026 — Cloud Dancer**, PANTONE 11-4201, about **#F0EEE9**. The first true white ever named, a warm aerated off-white. Use it as a calm canvas; pair with deep forest green, burnt sienna, or rich navy. As a text color it needs a dark surface behind it.

### Ready-to-use palettes
Roles are labelled bg / surface / text / accent. All hex pulled from cited sources.

| Palette | Hex | Use |
|---|---|---|
| **Dark-mode blue-black + cyan** | `#0F172A` bg · `#1E293B` surface · `#E2E8F0` text · `#94A3B8` muted · `#38BDF8` accent | Premium fintech / SaaS dark UI |
| **Deep teal editorial** | `#004F4F` · `#0EA5A4` · `#E0F2FE` text · `#B2FF2E` accent | Blue-green is the 2026 direction; lime for energy |
| **Mocha warm neutrals** | `#F5F1E8` bg · `#A47864` · `#8A9A5B` · `#3A2E27` text | Earthy, luxe, grounded |
| **Acid / digital lime** | `#0B1220` bg · `#334155` · `#E2E8F0` text · `#7CFF00` accent | Hyper-digital accent on dark; badges only |
| **Pinterest 2026** | `#D7EFFF` · `#AEB8A0` · `#E9F056` · `#FF5C34` · `#351E28` text | Cool blue, jade, wasabi, persimmon, plum |
| **Dusty muted pastels** | `#8C88BA` · `#BF84AE` · `#DB95AC` · `#FBB9A6` · `#FDE4CA` | Grown-up pastel: lavender haze, dusty rose |
| **Cyberpunk duotone** | `#0D0221` bg · `#FF2A6D` · `#05D9E8` · `#D1F7FF` text | Bold tech, gaming, nightlife |
| **Navy + single accent** | `#1B2A4A` bg · `#2E4372` · `#F4F6FB` text · `#FF7A45` accent | Restrained, trustworthy, corporate |
| **Saffron earthy warm** | `#F5F1E8` bg · `#F4C542` · `#E97451` · `#2B2622` text | Heritage, organic, autumnal editorial |

### Gradients
- **Aurora (cool):** `#001F3F → #0E7490 → #14B8A6 → #A3E635 → #C084FC`
- **Pastel sunset:** `#FFF9C9 → #FFD497 → #FBA58B → #FB918F`
- **Duotone:** `#FF71CE → #01CDFE` (or Spotify-style `#1DB954 → #191414`)
- **Mesh:** place `#FF6B6B`, `#FFD93D`, `#6BCB77`, `#4D96FF` at corners, blend with radial-gradient + background-blend-mode.
Add grain texture and a tinted (not white) glass layer on top for the current feel.

### Accessibility
- **WCAG AA** is 4.5:1 for body text and 3:1 for large headings (≥24px, or 18.5px bold). **AAA** is 7:1 / 4.5:1.
- On dark backgrounds people read by **luminance**, so span a wide brightness range.
- **Grayscale-test** every palette. If it still reads in gray, it survives color blindness.
- Use **pattern fills** on charts (hatch, dots) so color is never the only signal.
- **Okabe-Ito** colorblind-safe set: `#E69F00 #56B4E9 #009E73 #F0E442 #0072B2 #D55E00 #CC79A7 #000000`. On dark backgrounds drop the black and lean on yellow, sky, orange. **Paul Tol "Light"** is built for dark backgrounds: `#77AADD #99DDFF #44BB99 #BBCC33 #AAAA00 #EEDD88 #EE8866 #FFAABB #DDDDDD`.

### Building a palette
- **60-30-10:** 60% dominant neutral (background), 30% secondary surfaces, 10% accent for CTAs and highlights. Keep the accent scarce, like punctuation.
- **One accent:** pick a single high-chroma color and let everything else stay neutral. Two competing brights fight.
- **Warm neutrals:** use #1C1917 or #0F172A instead of pure black, and #F0EEE9 instead of pure white. The signature 2026 move is one organic earthy tone with one sharp digital accent.

---

## 3. Typography

### What's trending in 2026
- **Neo-grotesques are overtaking geometric sans** for professional work (Söhne and Inter over Gotham and Proxima). Geometric-sans fatigue is real.
- **Variable fonts are infrastructure now**, not a novelty: one file, multiple axes (weight, width, optical size, grade). Use them wherever offered.
- **Big bold display type** at 80pt+ as the hero element, with type filling up to half a slide.
- **High-contrast revival serifs** for editorial and trust; "Mutant Heritage" means classic letterforms hacked off-kilter.
- **Monospace as display** beyond code (JetBrains Mono, Space Mono), and **expressive or quirky display faces** for personality.

### Fonts that look premium and are free
| Font | Class | Vibe | Source |
|---|---|---|---|
| **Inter** | humanist sans | neutral screen-optimized UI default | Google Fonts |
| **Geist** | modern grotesque | sharp, tech/dev-tool default; has Geist Mono | Google Fonts / Vercel |
| **Space Grotesk** | proportional grotesque | engineered, deliberate; headings | Google Fonts |
| **Satoshi** | geometric-humanist (variable) | modernist, versatile | Fontshare |
| **General Sans** | rationalist sans | orderly yet lively body | Fontshare |
| **Clash Display** | neo-grotesque display | eye-catching at large sizes | Fontshare |
| **Fraunces** | high-contrast serif (variable) | expressive, old-meets-new | Google Fonts |
| **Instrument Serif / Sans** | editorial serif + sans | clean literary system | Google Fonts |
| **Bricolage Grotesque** | variable grotesque | "perfectly imperfect", warm | Google Fonts |
| **JetBrains Mono** | monospace | technical accent/display | Google Fonts |

Licensing flags: Fontshare faces (Satoshi, General Sans, Clash Display) are free for commercial use. "Editorial New" (a gorgeous display serif you'll see referenced) is free for personal use only; commercial use needs a Pangram Pangram license.

### Pairings that work
- **Fraunces / Inter** — characterful optical-size serif over a neutral sans; Inter never fights.
- **Clash Display / General Sans** — both Fontshare, shared DNA; display drama over rational calm.
- **Space Grotesk / Inter** — engineered display plus neutral body; the tech/startup signal.
- **DM Serif Display / DM Sans** — same superfamily, so coherence is built in.
- **Newsreader / Literata** — both screen-designed for reading; digital-magazine feel.
- **Superfamily shortcut:** IBM Plex, Source Sans/Serif, and PT families are pre-matched, so harmony is guaranteed.

**Principles:** contrast by classification or weight, cohere by shared x-height era, and give each face one job. The squint test: set both at the same size in black; if you can't tell which is which, they're too similar. Cap it at two families and three weights (say 400 / 500 / 700). Test at mobile sizes, where weight contrast collapses.

### Type scale & hierarchy
- **Ratios:** Major Third **1.25** for content-rich slides, Perfect Fourth **1.333** for more pop, Perfect Fifth **1.5** for posters and banners. Size = base × ratio^step.
- **Scale at 16px base (1.25):** Display 39 / H1 31 / H2 25 / H3 20 / Body 16 / Small 13.
- **Projected slides:** body 24–32pt, titles 80pt+. Web body 16px, slide body bumps up for viewing distance.
- **Line-height:** ~1.5 for body, 1.2–1.3 for headings.
- **Line length:** 50–75 characters (target ~65; `max-width: 65ch`). Left-align; avoid justified blocks.

---

## 4. Layout & grid

### Systems and principles
- **Grid types:** *Column* (simple title posters), *Modular* (columns plus rows, for complex content), *Baseline* (vertical rhythm where line-height equals baseline spacing), *Hierarchical* (importance-driven, freeform focal points, the most poster-relevant).
- **Spacing unit:** pick a 4px or 8px base and apply it to every padding, margin, and line-height for rhythm.
- **Rule of thirds:** a 3×3 grid; put focal elements on the intersections.
- **Whitespace** is an active tool. Let layouts breathe for a high-end feel.
- **Visual flow:** eyes scan in a **Z** pattern on sparse hero layouts and an **F** pattern on text-dense ones. Place key content where the eye lands first.
- **Break the grid on purpose** once the structure is established, for tension.

### Slide & poster layout patterns
- **Bento grid** — mixed content in one view; hierarchy by box size, largest holds the hero; max ~6 cells.
- **Full-bleed image or video** — emotional impact and openers; edge-to-edge media, text in one safe corner over a scrim. 10–60s clips are replacing static graphics.
- **Big number / hero metric** — one figure that must stick; giant numeral, accent on the number, the rest neutral.
- **Split 50/50** — concept plus visual, or two sides of a compare; one idea per half.
- **Pull-quote** — testimonial or editorial beat; oversized serif, wide margins, asymmetric.
- **Section divider** — chapter breaks; full-bleed color or type, a kicker label, little else.
- **Grid of cards** — parallel items (features, team, logos); uniform repeated modules.
- **Comparison / two-column** — before and after; mirrored columns, aligned rows.
- **Title + kicker** — the opener; a small eyebrow label above a large noun-phrase headline.
- **Timeline** — process or chronology; a horizontal flowline with evenly spaced nodes.

**2026 context:** dark mode with neon accents is becoming a boardroom default, glass and aurora gradients are replacing flat blocks, vertical 9:16 mobile-first decks are the fastest-growing format, and the editorial look (wide margins, serif, splashy quotes) is everywhere. One message per slide.

---

## 5. Make it: PowerPoint & decks

The default template look reads dated, so the craft is in the system you build.

- **Slide Master and custom layouts** are your one source of truth for type, color, and placeholders. Build a named layout per content type and edit the master, never individual slides.
- **Theme colors and fonts:** define a palette plus a heading/body pair once, so recoloring the theme cascades to every chart and shape.
- **Designer (Design Ideas):** AI layout suggestions in the right pane. Treat them as a starting point and then strip the clutter. Needs Microsoft 365.
- **Morph transition:** duplicate a slide, move or resize a shared object, and apply Morph for smooth motion. To force a clean 1:1 morph, prefix both objects' names with `!!` in the Selection Pane. Objects must be the same type; charts don't morph.
- **Icons and SVGs:** Insert > Icons gives crisp recolorable vectors. Right-click an SVG > Convert to Shape to edit individual paths.
- **Image treatment:** size photos to the slide edges for full-bleed, send to back, and lay a semi-transparent shape over them for text legibility. Recolor for a duotone. Compress pictures before delivery.
- **Tables and charts:** delete gridlines, borders, and redundant legends; label series directly; gray everything except the one series that matters; remove 3D and shadows.

**Deck craft, framework level:**
- **One idea per slide**, with size, weight, and space guiding the eye.
- **Assertion-Evidence (Michael Alley):** a full-sentence headline states the claim, and the body is one visual that proves it. It tests better for comprehension and recall than topic-plus-bullets, and it fits technical talks well.
- **Slidedocs (Nancy Duarte):** a read-not-projected medium for leave-behinds; denser, up to ~250 words a slide. Past that, write a document.
- **Presentation Zen (Garr Reynolds):** maximize signal-to-noise; the slides support the talk, they aren't the script.

**Tool landscape and the look each pushes:**
- **Gamma** — card-based, modern gradients, the most polished from a prompt; weak PowerPoint export.
- **Beautiful.ai** — smart rails keep you on-brand and make it hard to look bad; less freedom, cleaner export.
- **Pitch** — collaboration-first with clean startup templates; good for team investor decks.
- **Canva** — huge asset and template library, bold trendy look, great for non-designers.
- **Google Slides** — lightweight real-time collaboration, plain default look.
- **Apple Keynote** — best built-in animation (Magic Move equals Morph), refined themes; Mac and iOS only.
- **Copilot in PowerPoint** — turns a prompt or Word doc into a branded deck on your template; output uses topic titles and needs reformatting.
- **Tome** shut down its presentation product in 2025; drop it from new work.

---

## 6. Make it: HTML/CSS slides

Why bother instead of PowerPoint: plain-text decks live in Git, code blocks are first-class (real syntax highlighting, progressive reveals, live editing), and the browser ceiling means unlimited CSS animation and interactive components. Markdown decks are also AI-native, so a model can generate a valid deck, diagrams and all.

**Frameworks:**
- **Slidev** — Markdown plus Vue, the developer favorite (~38k stars). Live reload, Shiki code highlighting with Keynote-style "magic move" code morphing, presenter mode, export to PDF/PPTX/PNG. Strongest 2026 default for devs. It ships official AI agent skills and VS Code Copilot tooling.
- **reveal.js** — the mature, maximally flexible standard (~69k stars). Embeddable vanilla JS that drops into any site, biggest plugin ecosystem, remote audience control. Authored as HTML sections, so a slightly steeper start.
- **Marp** — minimalist Markdown to HTML/PDF/PPTX (~9k stars). Flattest learning curve, the best PowerPoint export, a VS Code live preview. Its 2026 update improved CSS theming.
- **Spectacle** — React/MDX deck library, actively maintained; good for React shops wanting live code demos.
- **impress.js** — 3D zoom-and-pan Prezi-style canvas; older and sporadically maintained, good for a one-off visual showpiece.
- Skip **mdx-deck** (unmaintained) and treat **WebSlides** and **Eagle.js** as low-activity; verify on GitHub before adopting.

**Techniques:** Shiki or Prism syntax highlighting with line-by-line reveals; Mermaid for diagrams; KaTeX for math; CSS Grid and Flexbox for layout; `scroll-snap` for a no-JS deck (arrow-key navigation, limited easing); Tailwind for slides via `tw-slide`; the View Transitions API for smooth morphs (still thin tooling); and print-to-PDF in every framework. Web fonts give you full control that PowerPoint's font embedding can't.

**Momentum:** Slidev is the clear developer default and is leaning hard into AI-assisted authoring; practitioners report deck time dropping from 3–4 hours to about one. Marp matured its theming, and Tailwind-native and Svelte options are filling in.

---

## 7. Posters & flyers

This is the most relevant section for academic conference work. Confirm the venue's size and format rules first; they vary.

### The academic poster
- **Traditional layout:** title bar, then Intro → Methods → Results → Discussion → References flowing down 3–4 columns, reading order vertical. Complete, expected by many committees, and criticized as a ten-minute read in a busy hall.
- **Better Poster / #betterposter (Morrison method):** a billboard format. One giant plain-language finding sits in the center, readable across the room; narrow sidebars hold method, a key figure, and limitations; a short "silent presenter" summary bar covers you when you're busy; a QR code links to the paper and figures. It is grounded in eye-tracking and instructional-design research, and exit surveys show most viewers prefer it. Some PIs and judges dislike it, so check the room. Portrait and landscape templates exist.
- **Sizing:** A0 (841×1189mm) international, 48×36" common in the US. Don't proportionally shrink a smaller poster; body text stays ≥24pt.
- **Type sizes at A0:** title 78–100pt bold; headings 36–60pt; body 24–36pt (never below ~24pt); captions 18–30pt. Readable from a meter, ideally from 4–7 feet.
- **Fonts and density:** sans-serif (Arial, Helvetica, or free Inter / Open Sans / IBM Plex Sans), 2–3 fonts max, left-aligned. Aim for roughly 20% text, 40% figures, 40% whitespace; word count ~300–600 at A0. Figures dominate, and less text draws more visitors.

### Poster tools
- **PowerPoint** as one giant slide set to poster dimensions, exported at 300dpi. The default for most grad students, and the Morrison templates are .pptx.
- **Canva** for fast browser-based work; advanced export needs a paid tier.
- **Affinity Publisher** for InDesign-class power as a one-time purchase.
- **Adobe InDesign / Illustrator** for publication-grade, press-ready output.
- **LaTeX** for equation-heavy, reproducible posters: **beamerposter** reuses beamer themes, **tikzposter** is the most flexible (and the steepest), **baposter** does compact grids. Always start from a template and review the PDF before printing.

### Event & promotional flyers
- **Hierarchy first:** decide where the eye goes, then use size, weight, color, and spacing to make it unambiguous. Whitespace removes noise.
- **Swiss / International style:** a mathematical grid as the backbone, asymmetric layout, flush-left sans, photography over illustration, minimal color. The grid is an aid, not a guarantee.
- **Typographic posters and color blocking:** one strong statement (4–8 words), the heaviest font filling 70–80% of the frame, and exactly 2–3 colors at scale.
- **2026 flyer trends:** maximalism and neo-brutalism, full-frame display type that acts as the image, saturated color blocking, and punk/zine/DIY collage with grain and monospaced or handwritten type (an explicitly anti-AI, reclaim-authorship move).

---

## 8. Personal & indie aesthetics

What signals "made with taste by an individual" in 2026.

- **Developer-portfolio look:** dark-mode-first (avoid pure black; #121212–#1C1C1E), tight type hierarchy, monospace for headings and code accents, generous whitespace, and the work itself as the hero rather than a headshot. The dominant credible look is Linear and Vercel influenced: high-contrast neutral grays, one desaturated accent, crisp small-radius cards. Built with Next.js or Astro plus Tailwind and shadcn/ui, with Geist or Inter for UI and JetBrains Mono or Geist Mono for the terminal vibe.
- **Terminal / monospace aesthetic:** monospace everything, syntax-highlighted blocks, terminal-style nav, typing animations. The best versions split type, using mono for precision and a serif for personality.
- **Indie-hacker landing pages:** an announcement pill, a large headline, subtext, and a CTA; a screenshot in a browser frame; a bento feature grid; testimonials and trust logos; mobile-first. The 2026 reality check: bento and dark mode held up, while heavy kinetic type and WebGL/3D often underdelivered on performance.
- **GitHub READMEs:** centered layouts, a hero banner, Shields.io badges, animated typing SVGs, and a snake contribution graph.
- **Retro / zine / neobrutalist anti-corporate:** thick outlines, hard offset shadows, eccentric type, bright flat colors, exposed UI. Keep contrast and readability or it alienates.
- **Tools individuals reach for:** Carrd and Framer for no-code; Astro and Next.js plus Tailwind and shadcn/ui for code; v0, Subframe, and Windframe for AI scaffolding; Figma, Canva, and Notion for the rest.

---

## 9. Resources
Galleries: Awwwards, Godly (godly.website), Land-book, Dribbble, Behance, Brutalist Websites, Lapa Ninja, Bento Grids.
Templates & decks: Better Poster (osf.io/ef53g), UC Davis and Yale poster guides, Slidesgo, Overleaf posters.
Frameworks & tools: Slidev (sli.dev), reveal.js, Marp, shadcn/ui, Aceternity UI, Spline, Framer.
Color & fonts: Coolors, Adobe Color, Realtime Colors, WebAIM contrast checker, Typewolf, Fontshare, Google Fonts, Fontpair.
Trend reports: Figma web-design-trends, Canva 2026 newsroom, Pinterest Palette, Fontfabric, NN/g (neobrutalism), Creative Boom.
The full clickable list with domains lives in the **Resources** section of [[Design Styles Gallery.html]].

---

## Sources & caveats
Built from a June 2026 web sweep across Figma, Canva, Creative Boom, Krumzi, Lummi, Fontfabric, Dezeen, IxDF, NN/g, Pantone, Pinterest, Adobe, Typewolf, Fontshare, Microsoft, Duarte, sli.dev, revealjs.com, marp.app, the #betterposter project (Mike Morrison), UC Davis and Yale library guides, and Overleaf.

A few honest flags:
- **Pantone hex values are approximate.** Mocha Mousse appears as #A47864 and #A47764, and Cloud Dancer as #F0EEE9 and #F0EFEB, because Pantone is a proprietary spot system.
- **Trend "rising/fading" calls are practitioner consensus, not measurement.** Weigh them against your own audience and venue, especially for academic settings where conservative layouts are still expected.
- **GitHub star counts are mid-2025 snapshots;** check live before choosing a framework.
- **Tool-comparison claims** sometimes come from competing vendors; verify export quality yourself.
- The **aurora/mesh hex stops** are constructed from the named 2026 trend hues; the individual colors are real, the exact combination is illustrative.


