---
version: alpha
name: FinalForm-design-system
description: |
  A merged, grounded wellness design language synthesized from three athletic/health brands — Oura, Cadence, and SATISFY — into one calm, premium, anti-subscription system for FinalForm. The page floor is a warm cream canvas (#f7f1e8) rather than white; a single warm dark-brown "ink" (#4a4741) does double duty as headline text and primary CTA fill — there is no saturated brand color. Typography is a deliberate two-family pairing: a light-weight editorial serif (Editorial New substitute) for hero and campaign statements, and a neutral grotesque (AkkuratLL substitute) for every functional label, with uppercase + wide-tracking micro-labels borrowed from the Cadence/SATISFY register. Shape language is soft and pill-dominant: every CTA is fully rounded, photography clips at 8px, and the hero and footer read as "sheets" with 48px radiused edges over the cream page. Elevation is essentially flat — separation comes from cream/charcoal banding, 1px hairlines, one ambient hero shadow, a frosted scroll-nav, and a calm blur-up reveal. It is the visual translation of the brand's thesis: 80% of premium health apps, delivered simple and free.

colors:
  primary: "#4a4741"
  primary-hover: "#1c1b1a"
  on-primary: "#f7f1e8"
  primary-disabled: "#e6ded3"
  signal-blue: "#2a72de"
  signal-blue-hover: "#2056a6"
  on-signal-blue: "#ffffff"
  cream-50: "#fefaef"
  cream-100: "#f7f1e8"
  cream-200: "#eee6dc"
  sandstone-300: "#efeae2"
  sandstone-450: "#e6ded3"
  white: "#ffffff"
  ink: "#4a4741"
  muted: "#838280"
  muted-soft: "#a8a5a0"
  hairline: "#d3d1ce"
  hairline-soft: "#ececec"
  divider: "#cbcbcb"
  surface-dark: "#1c1b1a"
  surface-dark-elevated: "#3a3837"
  surface-darkest: "#151619"
  on-dark: "#f7f1e8"
  on-dark-mute: "#838280"
  secondary-cream: "#fffee1"
  secondary-cream-hover: "#fffdc7"
  on-secondary-cream: "#000000"
  campaign-wash-taupe: "#baafa4"
  campaign-wash-yellow: "#f7e37e"
  campaign-wash-lime: "#dcdb7d"
  campaign-wash-moss: "#79b884"
  campaign-wash-steel: "#5c6e7c"
  campaign-wash-purple: "#897f98"
  success: "#55dc83"
  error: "#d22c15"
  badge-bg: "#444444"
  badge-text: "#ffffff"
  scrim: "rgba(0, 0, 0, 0.4)"

typography:
  display-serif:
    fontFamily: "'Editorial New', PPEditorialNew, 'Libre Caslon Text', 'Georgia', serif"
    fontWeight: 300
    letterSpacing: -0.05em
  display-xl:
    fontFamily: "'Editorial New', PPEditorialNew, serif"
    fontSize: 110px
    fontWeight: 300
    lineHeight: 1.1
    letterSpacing: -0.05em
  display-lg:
    fontFamily: "'Editorial New', PPEditorialNew, serif"
    fontSize: 72px
    fontWeight: 300
    lineHeight: 1.1
    letterSpacing: -0.05em
  display-md:
    fontFamily: "'Editorial New', PPEditorialNew, serif"
    fontSize: 48px
    fontWeight: 300
    lineHeight: 1.1
    letterSpacing: -0.05em
  serif-quote:
    fontFamily: "'Editorial New', PPEditorialNew, serif"
    fontSize: 30px
    fontWeight: 200
    lineHeight: 1.5
    letterSpacing: 0
  heading-6xl:
    fontFamily: "'AkkuratLL', Inter, -apple-system, system-ui, 'Helvetica Neue', sans-serif"
    fontSize: 80px
    fontWeight: 300
    lineHeight: 1
    letterSpacing: -0.025em
  heading-h1:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 60px
    fontWeight: 300
    lineHeight: 1
    letterSpacing: -0.025em
  heading-xl:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 40px
    fontWeight: 300
    lineHeight: 1
    letterSpacing: -0.025em
  heading-lg:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 32px
    fontWeight: 300
    lineHeight: 1.25
    letterSpacing: 0
  heading-base:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 28px
    fontWeight: 300
    lineHeight: 1.25
    letterSpacing: 0
  heading-sm:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: 0
  heading-xs:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: -0.025em
  body-lg:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-md:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-sm:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  caption:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: -0.025em
  eyebrow:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0.08em
    textTransform: uppercase
  overline:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0.13em
    textTransform: uppercase
  button-md:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  button-sm:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0
  nav-link:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  stat-number:
    fontFamily: "'AkkuratLL', Inter, sans-serif"
    fontSize: 72px
    fontWeight: 300
    lineHeight: 1
    letterSpacing: -0.025em

rounded:
  none: 0px
  sm: 4px
  md: 6px
  lg: 8px
  xl: 12px
  xl2: 16px
  xl3: 24px
  xl4: 32px
  sheet: 48px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  base: 24px
  lg: 32px
  xl: 48px
  xxl: 64px
  section: 96px
  container-gutter: 24px
  container-gutter-wide: 64px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.full}"
    padding: 12px 24px
    height: 48px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.full}"
  button-secondary:
    backgroundColor: "{colors.cream-100}"
    textColor: "{colors.primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.full}"
    padding: 12px 24px
    height: 48px
  button-secondary-cream:
    backgroundColor: "{colors.secondary-cream}"
    textColor: "{colors.on-secondary-cream}"
    typography: "{typography.button-md}"
    rounded: "{rounded.full}"
    padding: 12px 24px
    height: 48px
  button-blue:
    backgroundColor: "{colors.signal-blue}"
    textColor: "{colors.on-signal-blue}"
    typography: "{typography.button-md}"
    rounded: "{rounded.full}"
    padding: 12px 24px
  button-on-dark:
    backgroundColor: "{colors.cream-100}"
    textColor: "{colors.primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.full}"
    padding: 12px 24px
  button-outline-dark:
    backgroundColor: transparent
    textColor: "{colors.white}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.full}"
    padding: 8px 16px
    border: 1px solid white
  button-compact:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.full}"
    padding: 8px 16px
    height: 40px
  icon-button-circle:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    border: 1px solid rgba(74, 71, 65, 0.25)
    size: 48px
  card-arrow:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.full}"
    size: 48px
  eyebrow-badge:
    backgroundColor: "{colors.cream-100}"
    textColor: "{colors.ink}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.md}"
    padding: 8px 12px
  eyebrow-badge-on-dark:
    backgroundColor: "{colors.surface-dark-elevated}"
    textColor: "{colors.on-dark}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.md}"
    padding: 8px 12px
  primary-nav:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
    height: 90px
  nav-scroll-chrome:
    backgroundColor: rgba(74, 71, 65, 0.1)
    textColor: "{colors.primary}"
    rounded: "{rounded.lg}"
    border: 1px solid rgba(74, 71, 65, 0.25)
    backdropFilter: blur(2rem)
  tabs-underlined:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.none}"
    underline: 3px currentColor
  tab-active:
    textColor: "{colors.primary}"
    opacity: 1
    underline: 3px currentColor
  tab-inactive:
    textColor: "{colors.primary}"
    opacity: 0.7
    underline: 3px transparent
  ticker-band:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.overline}"
    height: 40px
  stat-tile:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.stat-number}"
    rounded: "{rounded.none}"
  stat-icon-circle:
    backgroundColor: "{colors.cream-200}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 60px
  testimonial-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.primary}"
    typography: "{typography.serif-quote}"
    rounded: "{rounded.lg}"
    border: 1px solid "{colors.hairline}"
    padding: 48px 40px
  news-card:
    backgroundColor: "{colors.cream-100}"
    textColor: "{colors.primary}"
    typography: "{typography.heading-sm}"
    rounded: "{rounded.lg}"
    padding: 24px
  email-input-dark:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xl}"
    padding: 8px 48px 8px 20px
    height: 40px
    shadow: inset 0 1px 0 rgba(255, 255, 255, 0.06)
  footer-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark-mute}"
    typography: "{typography.body-sm}"
    roundedTop: 48px
    padding: 64px 0
  hero:
    backgroundColor: "{colors.cream-100}"
    textColor: "{colors.primary}"
    roundedBottom: 48px
    shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25)
---

## Overview

FinalForm's design system is a **synthesis of three athletic/health brands** — Oura, Cadence, and SATISFY — distilled into a single grounded, calm, premium-but-free visual language that mirrors the brand's thesis: *80% of high-end health apps, delivered simple and free.*

- **From Oura** comes the warm cream canvas and the single warm dark-brown ink (`{colors.primary}` — #4a4741) that does double duty as headline text and primary CTA fill; the two-family editorial typography (light serif display + grotesque sans UI); pill-dominant CTAs; 8px image clipping; the frosted scroll-nav; the 48px radiused "sheet" edges; and the calm blur-up reveal motion.
- **From Cadence** comes the monochrome discipline and the editorial micro-label register — uppercase, wide-tracked buttons and eyebrows (0.08–0.13em) doing the labeling so hierarchy doesn't depend on weight; the marquee **proof/ticker band**; and the "data as display numerals" stat treatment.
- **From SATISFY** comes the flat, shadow-free surface discipline (depth from photography and banding, never drop shadows), the black/white (here cream/charcoal) banding rhythm, and the idea of **per-campaign color washes** — restrained accent hues used only as full-bleed section bands, never as decorative chrome.

There is **no saturated brand color.** The system's voltage is a warm dark ink; the only genuine accents are a restrained signal blue (sparingly, for action/eligibility moments) and optional campaign washes reserved for special full-bleed bands. Everything else lives on the cream-and-charcoal spectrum.

**Key Characteristics:**
- Warm cream page floor (`{colors.cream-100}` — #f7f1e8), not white. White is a card surface; charcoal is the band/footer.
- Dark CTA, not a colorful one: `{colors.primary}` (#4a4741) fills every primary pill with cream text; secondary pills invert.
- Two-family typography: editorial serif (light 200–300) for hero/campaign statements, grotesque sans (300/400) for every functional label; bold (700) reserved for buttons, badges, and eyebrows.
- Uppercase + wide-tracking micro-labels (eyebrows, overlines, buttons) borrowed from the Cadence/SATISFY register — labels do the labeling.
- Soft, pill-dominant shapes: 9999px CTAs, 8px image clipping, 48px radiused sheet edges (hero bottom, footer top).
- Flat elevation: separation via cream/charcoal banding + 1px hairlines + one ambient hero shadow + frosted nav chrome + blur-up reveal. No card shadows.
- A marquee **proof ticker** of credibility points (Cadence gesture) and **large display stat numbers** (Oura's `{typography.stat-number}`) for trust-signal moments.
- Calm Nordic copy voice: short, confident, no exclamation marks, no fake urgency.

## Colors

### Brand & Accent
- **Ink / Primary** (`{colors.primary}` — #4a4741): the single load-bearing color — headline text, body text, and primary CTA fill. A warm dark brown-gray that reads near-black but carries the cream's warmth.
- **Primary Hover** (`{colors.primary-hover}` — #1c1b1a): the pressed fill on primary pills — a true near-black.
- **On Primary** (`{colors.on-primary}` — #f7f1e8): cream text on dark pills. The inverted-cream relationship is the signature.
- **Signal Blue** (`{colors.signal-blue}` — #2a72de): the only saturated accent, used sparingly — action/eligibility moments (e.g., "FSA/HSA eligible", a header shop CTA). Hover `{colors.signal-blue-hover}` (#2056a6).
- **Secondary Cream** (`{colors.secondary-cream}` — #fffee1): a pale butter for secondary CTAs that sit inside photography (Cadence's warm signature). Hover `{colors.secondary-cream-hover}` (#fffdc7), black text.
- **Campaign Washes** (`{colors.campaign-wash-taupe}` #baafa4 · `{colors.campaign-wash-yellow}` #f7e37e · `{colors.campaign-wash-lime}` #dcdb7d · `{colors.campaign-wash-moss}` #79b884 · `{colors.campaign-wash-steel}` #5c6e7c · `{colors.campaign-wash-purple}` #897f98): restrained hues reserved for full-bleed section bands on special campaigns — never decorative chrome or buttons on white.

### Surface
- **Cream Canvas** (`{colors.cream-100}` — #f7f1e8): the page floor for hero, body, and most sections.
- **Cream Light** (`{colors.cream-50}` — #fefaef): the palest end, used for secondary-pill borders.
- **Sandstone Tints** (`{colors.sandstone-300}` — #efeae2; `{colors.sandstone-450}` — #e6ded3): progressive warm tints; the disabled/placeholder end doubles as `{colors.primary-disabled}`.
- **White** (`{colors.white}` — #ffffff): reserved for testimonial/card plates, payment pills, icon plates — not the page floor.
- **Dark Surface** (`{colors.surface-dark}` — #1c1b1a): the charcoal band (news strip, footer, ticker). **Dark Elevated** (#3a3837), **Darkest** (#151619) for gradients/overlays.

### Hairlines & Borders
- **Hairline** (`{colors.hairline}` — #d3d1ce): 1px card borders, section separators.
- **Hairline Soft** (`{colors.hairline-soft}` — #ececec): the lightest divider tier.
- **Divider** (`{colors.divider}` — #cbcbcb): the baseline rule under tab strips.

### Text
- **Ink** (`{colors.ink}` — #4a4741): default text on cream — headlines, paragraphs, nav, tabs.
- **Muted** (`{colors.muted}` — #838280): secondary text on light; also `{colors.on-dark-mute}` on charcoal.
- **Muted Soft** (`{colors.muted-soft}` — #a8a5a0): soft secondary headings, footnotes.
- **On Dark** (`{colors.on-dark}` — #f7f1e8): cream labels and headlines inside dark bands.

### Semantic
- **Success** (`{colors.success}` — #55dc83): good-score green, sparingly (check marks, readiness visuals).
- **Error** (`{colors.error}` — #d22c15): destructive/validation tone.
- **Badge** (`{colors.badge-bg}` — #444444, `{colors.badge-text}` — #ffffff): "NEW"/"Bestseller"-style tags.
- **Scrim** (`{colors.scrim}` — rgba(0,0,0,0.4)): modal/drawer backdrop.

## Typography

### Font Family
A deliberate **two-family pairing**:
- **Display serif** — an editorial light face (Editorial New substitute: **Libre Caslon Text** or **Cormorant Garamond**) loaded at light/ultralight (200–300) with an ultralight italic. Used for hero headlines, campaign statements, and italic emphasis words ("*your everyday*", "*the slow win*").
- **UI grotesque** — AkkuratLL substitute: **Inter** (300 light / 400 regular / 700 bold). Used for every structural heading, paragraph, nav link, button label, and badge.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.display-xl}` | 110px | 300 | 1.1 | -0.05em | Full-viewport hero statement |
| `{typography.display-lg}` | 72px | 300 | 1.1 | -0.05em | Hero at md/lg |
| `{typography.display-md}` | 48px | 300 | 1.1 | -0.05em | Hero at base; PDP stat numbers |
| `{typography.serif-quote}` | 30px | 200 | 1.5 | 0 | Testimonial quotes |
| `{typography.heading-6xl}` | 80px | 300 | 1 | -0.025em | Section headline tier |
| `{typography.heading-h1}` | 60px | 300 | 1 | -0.025em | Large section h1 |
| `{typography.heading-xl}` | 40px | 300 | 1 | -0.025em | Desktop section heads |
| `{typography.heading-lg}` | 32px | 300 | 1.25 | 0 | Tablet section heads |
| `{typography.heading-base}` | 28px | 300 | 1.25 | 0 | Base section head |
| `{typography.heading-sm}` | 24px | 400 | 1.25 | 0 | Card titles, news cards |
| `{typography.body-lg}` | 18px | 400 | 1.5 | 0 | Larger body, over-eyebrows |
| `{typography.body-md}` | 16px | 400 | 1.5 | 0 | Default paragraphs, footer wordmark |
| `{typography.body-sm}` | 14px | 400 | 1.5 | 0 | Attributions, fine copy |
| `{typography.overline}` | 14px | 400 | 1.2 | 0.13em (uppercase) | Kickers, ticker, section overlines |
| `{typography.eyebrow}` | 12px | 700 | 1.25 | 0.08em (uppercase) | Badges ("FEATURED", "FSA or HSA eligible") |
| `{typography.button-md}` | 16px | 700 | 1 | 0 | Standard pill CTA labels |
| `{typography.button-sm}` | 14px | 700 | 1 | 0 | Compact pills, outline buttons |
| `{typography.nav-link}` | 16px | 400 | 1.5 | 0 | Top nav links |
| `{typography.stat-number}` | 72px | 300 | 1 | -0.025em | Trust/stat figures |

### Principles
1. **Weight is restrained; size does the work.** Display runs at 300 (light); body at 400; bold (700) only for buttons, badges, and over-eyebrows. There is no 500/600 tier in active use — hierarchy jumps 300 → 400 → 700.
2. **Serif for voice, sans for chrome.** The editorial serif appears only in hero statements and italic emphasis; every functional label is the grotesque.
3. **Labels do the labeling.** Uppercase + wide tracking for overlines (0.13em), eyebrows (0.08em), and buttons — the Cadence/SATISFY register that lets a calm site still feel designed.
4. **Two tracking personalities.** Display serif -0.05em; sans headings -0.025em; body 0. Headline leading 1.0–1.25; body 1.5.
5. **Italic emphasis is a brand gesture.** Accent words inside headlines set in the serif ultralight italic.

### Note on Font Substitutes
AkkuratLL → **Inter** (within ~2% at body sizes). Editorial New → **Libre Caslon Text** or **Cormorant Garamond** (both carry the light/ultralight serif range with usable italics). Keep display at 300, UI at 400/700; preserve the -0.05em display tracking. If a monospace accent is ever needed for "lab-notebook" data labels (the SATISFY trick), use **IBM Plex Mono** with ~0.8px tracking.

## Layout

### Spacing System
- **Base unit:** 4px. Token steps: 4 · 8 · 12 · 16 · 24 · 32 · 48 · 64 · 96px.
- **Button padding:** standard pills `12px 24px`; compact `8px 16px`.
- **Card padding:** news cards 24px; testimonial cards `48px 40px`.
- **Section rhythm:** ~96px (`{spacing.section}`) for major bands, with 32–64px inner steps; the site breathes like a magazine spread — one primary object per scroll, not a dense marketplace.
- **Gutters:** 24px side gutters at desktop, widening to 64px at very wide viewports.

### Grid & Container
- **Max content width:** ~1440px, via a 22-column grid (`gridContainerV3`) with 24px (→64px) side gutters.
- **Column usage:** sections span main-to-main (full content width) or narrower bands; feature rows split text (left ~7 cols) next to media (right ~9 cols).
- **Home structure (FinalForm landing):** full-viewport cream hero with centered type + email capture → proof/ticker band → "why / origin" editorial band → tool feature grid → comparison section → paid-system upsell band → FAQ → dark footer sheet. Photography/motion stages between bands.

### Whitespace Philosophy
Generous, calm, and image-led. Cream-on-cream sections are separated by whitespace, layered media, and the occasional charcoal band — not by contrast grids. The brand reads as an editorial spread for wellness, not a marketplace.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 — Flat | No border, no shadow | Most imagery, stat tiles, cards, feature rows |
| 1 — Hairline border | 1px `{colors.hairline}` (#d3d1ce) | Testimonial cards, section separators |
| 2 — Inset highlight | `inset 0 1px 0 rgba(255,255,255,0.06)` | Dark email input |
| 3 — Hero shadow | `0 25px 50px -12px rgba(0,0,0,0.25)` | The only ambient shadow, under the hero band |
| 4 — Frosted chrome | 1px `rgba(74,71,65,0.25)` + `rgba(74,71,65,0.1)` + `backdrop-blur(2rem)` | Scroll-triggered nav pill |

There is **no progressive card-shadow ladder.** Depth comes from: (a) cream/charcoal banding, (b) 48px radiused "sheet" edges on the hero and footer, (c) layered photography and app-UI screenshots in 8px-clipped "mask" containers, and (d) the blur-up reveal (5px blur → 0 with opacity, on scroll). The only drop shadow is the hero's; the only glass effect is the scroll nav.

## Components

### Buttons
- **`button-primary`** — the universal CTA: `{colors.primary}` (#4a4741) fill, cream text, 16px/700, pill, `12px 24px`, ~48px. Hover deepens to `{colors.primary-hover}` (#1c1b1a).
- **`button-secondary`** — the inverted pair: cream fill, ink text, same pill geometry. Hover lifts fill toward gray.
- **`button-secondary-cream`** — Cadence's warm butter (`{colors.secondary-cream}` #fffee1, black text) for secondary CTAs inside photography.
- **`button-blue`** — `{colors.signal-blue}` fill, white text; reserved for action/eligibility moments, used sparingly.
- **`button-on-dark`** — cream pill with ink text for dark bands.
- **`button-outline-dark`** — transparent, 1px white border, white text, pill (over video/photography).
- **`button-compact`** — smaller pill (14px/700, `8px 16px`, ~40px) for header/hero actions.
- **`icon-button-circle`** / **`card-arrow`** — 48px circles: bordered icon button for cart/menu; filled dark arrow button on cards.

### Navigation
- **`primary-nav`** — sticky, transparent at rest over the cream hero, wordmark left + links + cart/menu right. On scroll, a frosted pill (`nav-scroll-chrome`) fades in. Nav links 16px/400 in ink with an optional text-stroke hover (no layout shift).
- **`tabs-underlined`** — bare-text tab strip with a 3px bottom rule: active = currentColor, inactive = transparent at 70% opacity; a 1px `{colors.divider}` baseline beneath.

### Proof & Trust Surfaces
- **`ticker-band`** — a marquee of credibility capsules ("Zero Sugar · 500mg Sodium · Dosed Right" / "4.8 | 2400+ reviews · Third-party tested") in `{colors.surface-dark}` with uppercase `{typography.overline}` text — the brand's recurring credibility device.
- **`stat-tile`** — a 60px circular icon plate + the figure in `{typography.stat-number}` (72px/300) + label + caption. For "80% of premium apps", "per-gram accuracy", etc.
- **`eyebrow-badge`** / **`eyebrow-badge-on-dark`** — 12px/700 uppercase badges, cream fill (or elevated-dark fill on dark bands), `{rounded.md}`, `8px 12px`.

### Cards
- **`testimonial-card`** — white plate, `{rounded.lg}` (8px), 1px `{colors.hairline}`, padding `48px 40px`; serif quote (30px/200) + muted attribution. The only white card — used precisely to stand off the cream page.
- **`news-card`** — cream cards on the dark band, `{rounded.lg}`, 24px padding, 24px/400 title, terminated by a `{component.card-arrow}`.

### Forms
- **`email-input-dark`** — the footer newsletter input: `{colors.primary}` fill, white text, `{rounded.xl}` (12px), padding `8px 48px 8px 20px` with a right-aligned submit, inset highlight. (Cadence's underline-newsletter and Oura's dark input both satisfy the system; the dark input is the default.)

### Footer & Hero
- **`hero`** — full-viewport cream band (`{colors.cream-100}`), centered type, `{roundedBottom}` 48px, the system's only ambient shadow.
- **`footer-dark`** — dark sheet (`{colors.surface-dark}`), top edge radiused 48px, radial gradient `{colors.surface-dark-elevated}` → `{colors.surface-dark}`, 64px vertical padding, muted cream text.

## Responsive Behavior

| Name | Width | Key Changes |
|---|---|---|
| Base (mobile) | < 768px | 8-column grid, 24px gutters; hero display at `{typography.display-md}` (48px); primary CTAs go full-width; nav collapses to wordmark + icon circles; news cards ~75vw; scenario tabs swipeable |
| md (tablet) | 768px | Grid widens to 22 columns; hero steps to 72px; responsive CTAs flip dark↔cream; payment row stacks |
| lg (desktop) | 1024px | Hero type at 96px; section heads reach 80px; feature rows go 2-column; news band padding 32→64px |
| xl / xxl | 1280/1440px | Hero caps at 110px; content maxes at 1440px |
| super | 1568px+ | Grid gutters widen 24→64px |

### Touch Targets
- Primary CTAs ~48px; compact pills ~40px with 16px padding.
- Icon/arrow circles 40px at mobile → 48px at md (at/above WCAG AA).
- Tabs carry a ~48px tap row.

### Collapsing Strategy
- Nav → wordmark + cart/menu circles below md.
- Hero stays full-viewport with centered type at all sizes.
- Feature rows collapse to stacked image + text.
- Ticker band: desktop/mobile copy variants so the marquee stays readable.
- CTAs may invert dark↔cream responsively.

## Do's and Don'ts

### Do
- Build the page on the cream canvas (`{colors.cream-100}` — #f7f1e8). White is a card surface, not the page floor.
- Let `{colors.primary}` (#4a4741) do double duty: headline text AND primary CTA fill — the system's only "dark accent."
- Keep CTAs fully pill-shaped with cream text and a hover deep to `{colors.primary-hover}`.
- Use the editorial serif (light/ultralight, -0.05em) for hero/campaign statements only; use the grotesque for every functional label.
- Set display headlines in weight 300 with tight leading/tracking; reserve bold 700 for buttons, badges, and over-eyebrows.
- Use uppercase + wide tracking for overlines, eyebrows, and buttons — labels do the labeling.
- Clip photography at 8px and radius the hero/footer sheet edges at 48px.
- Punctuate the cream scroll with charcoal bands (`{colors.surface-dark}`) and a marquee proof ticker.
- Animate with the blur-up reveal (5px → 0). Nothing springy, nothing urgent.

### Don't
- Don't introduce a saturated CTA color. The CTA is warm dark ink; signal blue is a rare action accent; campaign washes are full-bleed bands only.
- Don't set headlines in heavy weights — 300 light is the display voice; 700 is for buttons/badges.
- Don't float cards on shadows. No card-shadow ladder; use hairlines and banding.
- Don't render the footer light — it is `{colors.surface-dark}`.
- Don't put buttons on sharp corners — every interactive element is a pill.
- Don't use white as the body background.
- Don't use accent hues as decorative buttons/icons on cream — they are washes or rare action accents.
- Don't break the tracking discipline: display -0.05em, headings -0.025em, body 0.

## Known Gaps

- **Merged synthesis, not a single live product.** This system unifies three brands' extracted tokens; some component treatments (e.g., testimonial card, dark input, ticker) are composites chosen for FinalForm rather than observed in one place.
- **Authenticated/app chrome** (member dashboards, scores, ring UI) is not included — wellness data visualization is out of scope for the marketing system.
- **Form validation/error states** are not captured; `{colors.error}` is defined but marketing usage is unverified.
- **Checkout** (for the paid system) is not captured; pill CTA + dark input conventions are assumed to carry through.
- **Font licenses:** the serif and grotesque substitutes (Libre Caslon Text / Cormorant Garamond, Inter) are open-source; exact optical behavior of a 110px light serif is inferred.
- **Motion values** (blur-up timing/easing) are described conceptually; exact durations should be tuned in the browser.
- **Dark mode:** the marketing surface is cream-only with intentional dark bands; no dark-mode variant is defined.
