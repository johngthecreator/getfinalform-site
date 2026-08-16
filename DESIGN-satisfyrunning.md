---
version: alpha
name: Satisfy-design-analysis
description: |
  A gritty, drop-culture athletic brand with a brutalist editorial chrome: a Paris-founded running label ("Running apparel developed to unlock the High") built on a Shopify Dawn base, reskinned around two licensed display faces — ABC Simon Mono, a monospace for body copy, and ABC Walter Neue, a Swiss-style grotesque with an Extrafett (900) display cut that carries the entire typographic hierarchy. The canvas is near-pure black/white: white product pages, black mega-menu and footer bands, with per-drop color schemes injecting restrained accent hues — a chalky taupe #baafa4, signal yellow #f7e37e, lime-olive #dcdb7d, moss green #79b884, steel blue #5c6e7c, muted purple #897f98 — used as full-bleed section washes, never as decorative chrome. Shape language is mostly flat and hard: product imagery at 0px radius, buttons at 6px, inputs at 5px, pills at 16px, swatches and slider orbs as full circles (100px). The system has no shadow elevation — every shadow variable in the theme is pinned to 0.0 opacity; depth comes from full-bleed photography, uppercase tracked overlines (kickers), huge 900-weight Walter headlines that clamp 28–48px, and the visual shock of black/white banding.

colors:
  primary: "#000000"
  on-primary: "#ffffff"
  primary-inverse: "#ffffff"
  on-inverse: "#000000"
  canvas: "#ffffff"
  surface-soft: "#f8f9f9"
  surface-off: "#f3f4f4"
  surface-sand: "#fefff2"
  surface-taupe: "#baafa4"
  surface-dark: "#000000"
  on-dark: "#ffffff"
  ink: "#000000"
  gray-90: "#e5e5e5"
  gray-92: "#e8e9eb"
  gray-87: "#dbdfe0"
  gray-81: "#cfcfcf"
  gray-72: "#b9b6b6"
  gray-71: "#b6b6b6"
  gray-95: "#f3f4f4"
  gray-97: "#f8f9f9"
  accent-yellow: "#f7e37e"
  accent-lime: "#dcdb7d"
  accent-green: "#79b884"
  accent-steel: "#5c6e7c"
  accent-taupe: "#baafa4"
  accent-purple: "#897f98"
  accent-gray-brown: "#5c5951"
  hairline: "rgba(0,0,0,0.08)"
  hairline-medium: "rgba(0,0,0,0.2)"
  progress-track: "#b6b6b6"
  focus-outline: "rgba(0,0,0,0.5)"

typography:
  display-xxl:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 48px
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: -0.3px
  display-xl:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 40px
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: -0.3px
  display-lg:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 28px
    fontWeight: 900
    lineHeight: 1.2
    letterSpacing: -0.56px
  heading-xl:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: -0.48px
  heading-md:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 20px
    fontWeight: 900
    lineHeight: 1.25
    letterSpacing: -0.35px
  heading-sm:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: 0
  body-mono:
    fontFamily: "'ABC Simon Mono', monospace"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.8
    letterSpacing: 0.96px
  body-mono-lg:
    fontFamily: "'ABC Simon Mono', monospace"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.8
    letterSpacing: 0.96px
  price-display:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 20px
    fontWeight: 900
    lineHeight: 1
    letterSpacing: -0.4px
  caption-overline:
    fontFamily: "'ABC Simon Mono', monospace"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 2.08px
    textTransform: uppercase
  micro-overline:
    fontFamily: "'ABC Simon Mono', monospace"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0.64px
    textTransform: uppercase
  button:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: 1.6px
    textTransform: uppercase
  button-sm:
    fontFamily: "'ABC Walter Neue', 'Helvetica Neue', Helvetica, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: 1.2px
    textTransform: uppercase
  nav-link:
    fontFamily: "'ABC Simon Mono', monospace"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.6px
    textTransform: uppercase

rounded:
  none: 0px
  xs: 5px
  sm: 6px
  md: 16px
  lg: 25px
  xl: 40px
  pill: 100px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  base: 24px
  lg: 32px
  xl: 40px
  xxl: 48px
  section-desktop: 72px
  section-mobile: 50px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 12px 32px
    height: 48px
  button-inverse:
    backgroundColor: "{colors.primary-inverse}"
    textColor: "{colors.on-inverse}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 12px 32px
    height: 48px
  button-pill:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.md}"
    padding: 7px 23px
  icon-button-circle:
    backgroundColor: "{colors.gray-90}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: 50px
  text-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-mono}"
    rounded: "{rounded.xs}"
    borderWidth: 1px
    borderOpacity: 0.55
    height: 56px
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    padding: 0 32px
    height: 64px
  announcement-bar:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.micro-overline}"
  mega-menu:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
  mega-menu-cta-title:
    typography: "{typography.display-md}"
    fontWeight: 900
    textTransform: uppercase
  product-card:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.body-mono}"
    rounded: "{rounded.none}"
    textAlignment: center
  product-card-swatch:
    backgroundColor: "transparent"
    rounded: "{rounded.pill}"
    size: 12px
  product-card-price:
    typography: "{typography.body-mono}"
    letterSpacing: 1.6px
  collection-hero:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-lg}"
  collection-hero-overline:
    typography: "{typography.caption-overline}"
    textTransform: uppercase
  cart-drawer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    width: 525px
  cart-progress-track:
    backgroundColor: "{colors.progress-track}"
    rounded: "{rounded.lg}"
    height: 4px
  cart-progress-value:
    backgroundColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    height: 4px
  newsletter-form:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.body-mono}"
    maxWidth: 576px
  footer-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-mono}"
  footer-heading:
    typography: "{typography.nav-link}"
    textTransform: uppercase
  swatch-tile:
    backgroundColor: "transparent"
    rounded: "{rounded.pill}"
    size: 12px
  slider-progress-dot:
    backgroundColor: "rgba(185,182,182,0.5)"
    rounded: "{rounded.lg}"
    height: 2px
  slider-progress-dot-active:
    backgroundColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    height: 2px
---

## Overview

SATISFY is the Paris-founded running label behind "Running apparel developed to unlock the High." The site — a Shopify Dawn theme (schema 15.3.0) heavily reskinned with a Tailwind v4 design-token layer and two licensed fonts — reads as **gritty premium athletic**: deliberately anti-corporate, drop-culture commerce wrapped in an editorial, almost brutalist chrome. Product photography is the load-bearing element; the chrome around it is disciplined to black, white, and a small ramp of warm greys, with per-drop color-scheme washes (taupe, signal yellow, lime, moss green, steel blue, muted purple) appearing only as full-bleed section backgrounds, never as decorative accents.

The typographic personality is unmistakable: **monospace body copy** (`ABC Simon Mono`) for labels, meta, prices, nav, and long copy, paired with **`ABC Walter Neue`** — a Swiss grotesque whose Extrafett (weight 900) cut powers every headline. Almost every label on the site is set in uppercase with wide tracking (`letter-spacing: .06rem`–`.13rem`), including the SHOP CTAs ("FINAL HEAT", "EMBRACE THE SEASON", "FREE SHIPPING ABOVE 200 USD. FREE RETURNS."). Headlines clamp between 28px and 48px at weight 900; there is no light-weight heading anywhere.

The shape language is flat and hard where the product is, and only slightly softened in the machinery: product cards and gallery media run at **0px radius**, buttons at **6px**, inputs at **5px**, pills at **16px**, swatches and slider orbs as full circles. The entire system has **no shadow elevation** — every shadow variable in the theme (`--media-shadow-opacity`, `--product-card-shadow-opacity`, `--buttons-shadow-opacity`, `--inputs-shadow-opacity`, `--popup-shadow-opacity`, `--drawer-shadow-opacity`, `--text-boxes-shadow-opacity`) is pinned to `0.0`. Depth is manufactured from photography, hard black/white section banding, and typographic scale — not from layering.

**Key Characteristics:**
- **Monospace body / heavy grotesque display**: `ABC Simon Mono` (body, labels, prices, nav) + `ABC Walter Neue` Extrafett 900 (every headline). The single most distinctive trait in the system.
- **Uppercase-with-tracking everywhere**: kicker overlines ("FINAL HEAT"), nav, buttons, announcement bar, unit prices, badge labels. `text-transform: uppercase` appears 12+ times in the theme CSS.
- **Flat, shadow-free surfaces**: all theme shadow variables are `0.0` opacity. No card elevation, no hover lift — product images swap on hover (front → back) instead.
- **Hard product geometry, soft machinery**: 0px radius product media, 6px buttons, 5px inputs, 16px pills, full-circle swatches and slider orbs.
- **Black/white banding**: white product surfaces, black mega-menu, black footer, dark hero overlays — alternated for editorial rhythm.
- **Drop-culture IA**: "NEW ARRIVALS / FINAL HEAT / DESERT RATS / FOUNDATIONS" named collections, technology-first naming (MothTech™, Space-O™, AuraLite™, PeaceShell™), a "PRO TEAM" page, and a "Possessed" magazine.
- **Per-drop color schemes** (`#baafa4`, `#f7e37e`, `#dcdb7d`, `#79b884`, `#5c6e7c`, `#897f98`): full-bleed section washes that rotate by collection, keeping mainline chrome monochrome.
- **1200px+ container**: `--page-width: 160rem` (~1600px) with 32px grid gutters and 72px section rhythm at desktop.

## Colors

> **Source pages:** `/` (home), `/products/therocker-aluminum` (product), `/collections/shop-new-arrivals` (collection). Color values below are extracted from the page's embedded Shopify color-scheme variables and the theme's Tailwind `--color-*` tokens, both of which are served in the page HTML / stylesheet — no obfuscation.

### Brand & Accent
- **Black** (`{colors.primary}` — `#000000`): the de-facto brand color. Used as `--color-button` on every light scheme (primary CTA fill), foreground on `color-scheme-1/2/3`, and the brand wordmark. On dark schemes the button inverts to white.
- **White** (`{colors.on-primary}` — `#ffffff`): button text on black, and the inverse button fill on dark surfaces.
- **Signal Yellow** (`{colors.accent-yellow}` — `#f7e37e`): `color-scheme-f2f22baf` foreground / badge tone. Used on select collection treatments.
- **Lime-Olive** (`{colors.accent-lime}` — `#dcdb7d`): `color-scheme-8845109c` button color on white — an editorial CTA accent used on one homepage product-rail scheme.
- **Moss Green** (`{colors.accent-green}` — `#79b884`): `color-scheme-96d4134c` — green button + text on black.
- **Steel Blue** (`{colors.accent-steel}` — `#5c6e7c`): `color-scheme-d1ede939` foreground on white.
- **Muted Purple** (`{colors.accent-purple}` — `#897f98`): `color-scheme-f000c70c` foreground on white.

### Surface
- **Canvas** (`{colors.canvas}` — `#ffffff`): default page floor for the entire commerce experience — product grids, PDPs, cart drawer, mega-menu.
- **Surface Soft** (`{colors.surface-soft}` — `#f8f9f9`): `color-scheme-2` / `--color-gray-97` — the lightest warm grey wash, used for soft section bands.
- **Surface Off** (`{colors.surface-off}` — `#f3f4f4`): `--color-white-off` / `--color-custom-gray-95`.
- **Surface Sand** (`{colors.surface-sand}` — `#fefff2`): `color-scheme-3` — a pale cream used for a homepage band.
- **Surface Taupe** (`{colors.surface-taupe}` — `#baafa4`): `color-scheme-5` — a chalky warm sand, the closest thing to a seasonal hero wash; white text on it.
- **Surface Dark** (`{colors.surface-dark}` — `#000000`): `color-scheme-4` — the black footer, black collection CTAs, and dark hero overlay bands.
- **Warm Gray-Brown** (`{colors.accent-gray-brown}` — `#5c5951`): `color-scheme-478d0189` / `--color-gray-dark` — dark warm grey band with white text.

### Hairlines & Borders
- **Hairline** (`{colors.hairline}` — `rgba(0,0,0,0.08)`): the header bottom rule (`border-bottom: .1rem solid rgba(foreground, .08)`), table row separators, disclosure dividers.
- **Hairline Medium** (`{colors.hairline-medium}` — `rgba(0,0,0,0.2)`): stronger dividers — drawer footer `details` rows, popular-countries rules, border-left of blockquotes.
- **Swatch outline** (`rgba(0,0,0, 0)` → `--color-custom-gray-71`): swatch color items carry a `0 0 0 1px #b6b6b6` ring.
- **Mobile filter chip border** (`--color-custom-gray-87` `#dbdfe0`): pill filter labels outlined in light grey.

### Text
- **Ink** (`{colors.ink}` — `#000000`): the only text color in mainline light themes (`--color-foreground: 0,0,0`). True black, not a soft ink.
- **On Dark** (`{colors.on-dark}` — `#ffffff`): text on black bands and dark hero imagery.
- **Muted ink** (opacity-based, not hex): the theme renders secondary text via alpha — `rgba(0,0,0,.5)` (inactive slider numbers), `rgba(0,0,0,.7)` (unit price), `rgba(0,0,0,.75)` (sale strikethrough, disclosure links). There is no grey text token; greys are used as fills and borders.

### Semantic
- **Focus outline** (`rgba(0,0,0,0.5)`): `outline: .2rem solid rgba(var(--color-foreground), .5)` — a black 2px outline with `outline-offset: -.2rem` on localization selects; card heading links use a soft `rgba(foreground, .3)` halo.
- **Error / success**: not present in the extracted surfaces (no form validation states visible).
- **Cart threshold**: progress track `#b6b6b6`, progress value `#000000` — the only two-tone progress treatment in the system.

### Grey Ramp (custom tokens in `main.css`)
`--color-custom-gray-71` `#B6B6B6` · `--color-custom-gray-72` `#B9B6B6` · `--color-custom-gray-81` `#CFCFCF` · `--color-custom-gray-87` `#DBDFE0` · `--color-custom-gray-90` `#E5E5E5` · `--color-custom-gray-92` `#E8E9EB` · `--color-custom-gray-95` `#F3F4F4` · `--color-custom-gray-97` `#F8F9F9`. These power icon-button circles, slider orbs, filter-chip borders, and soft band washes — always as fill/border, never as text.

## Typography

### Font Family
Two licensed faces carry the entire system:

- **`ABC Simon Mono`** — body, meta, labels, prices, navigation, unit prices, badge text. Weights 400 / 500 (Medium cut). A monospace that gives the store its tech-spec / lab-notebook voice.
- **`ABC Walter Neue`** — every heading, button label, price-display, and mega-menu CTA. Weights 400 (Normal) and **900 (Extrafett)**, plus italic cuts (`NormalKursiv`, `ExtrafettKursiv`). The Extrafett is the display voice — used for the giant section titles, the brand wordmark lockups, and the collection-page H1s.

The Dawn base also loads **Assistant** (400/700) as the stock fallback, and `--font-heading-family`/`--font-body-family` are overridden at the `:root` level to the two ABC faces. A broader editorial font wardrobe is registered in the Tailwind token layer but not observed in active page chrome: `Baldur`, `Diatype-Medium`, `ITC Garamond Std`, `Slab / PP Right Slab`, `Arial Black`.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.display-xxl}` (`.hxl-fluid`) | clamp(32px, 3vw, 48px) | 900 | 1.1 | tight | Fluid hero headline lockups |
| `{typography.display-xl}` (`.hxxl`) | clamp(28px, 40px, 40px) | 900 | 1.1 (44px) | -0.3px | Section hero titles ("Space-O™", "Foundations") |
| `{typography.display-lg}` (h1) | 28px | 400 / 900 | 1.2 | -0.56px | Collection-page H1 ("Collection: New Arrivals"), PDP title |
| `{typography.heading-xl}` (h2) | 24px (18px mobile) | 400 | 1.2 | -0.48px | Section headings |
| `{typography.heading-md}` (h3) | 20px (18px mobile) | 900 | 1.25 | -0.35px | Card titles, block headings |
| `{typography.heading-sm}` (h4/h5) | 18px / 16px | 400 | 1.25 | 0 | Sub-headings |
| `{typography.body-mono}` | 14px | 400 | 1.8 | 0.96px | Base body (`body { font-size: .875rem; letter-spacing: .06rem }`) |
| `{typography.price-display}` | 20px (25.6px @desktop) | 900 | 1 | -0.4px | PDP price (`--price--large: 1.6rem`, weight 900) |
| `{typography.caption-overline}` | 16px | 400 | 1.2 | 2.08px | `.caption-with-letter-spacing` kickers, uppercase |
| `{typography.micro-overline}` | 11px | 400 | 1.2 | 0.64px | Unit prices (`1.1rem`, `.04rem`, uppercase), micro labels |
| `{typography.button}` | 14px | 400 | 1 | 1.6px | `.button` labels (`.875rem`, `.1rem`, uppercase) |
| `{typography.button-sm}` | 12px | 400 | 1 | 1.2px | Compact pills, chips |
| `{typography.nav-link}` | 12px | 400 | 1.5 | 0.6px | Nav / menu links, uppercase |

Observed letter-spacing vocabulary: `.1rem` (1.6px) buttons · `.13rem` (2.08px) overline kickers · `.06rem` (0.96px) base body · `-.03rem` / `-.035rem` negative heading tracking on h2/h3 · `.04rem` unit prices · `-.0175rem` dense inline labels.

### Principles
The system trusts **weight contrast over color contrast**: 900-weight Walter headlines against 400-weight Simon Mono body on pure black/white, with no mid-grey text. Uppercase + wide tracking is the default register for anything that isn't a long-form paragraph — the brand reads like an instruction manual for a race. Headlines are relatively compact (max 48px) and rely on the Extrafett cut's density rather than sheer size; the biggest text moment is the mega-menu / collection-hero treatment where titles run in `min(1.75vw, 25px)` at weight 900 over photography.

### Note on Font Substitutes
Both faces are commercial (ABC Type). Closest open-source substitutes: **IBM Plex Mono** for `ABC Simon Mono` (identical monospace voice, slightly wider tracking — reduce to ~0.8px), and **Inter Tight** (weights 700–900) or **Archivo Black** for `ABC Walter Neue` Extrafett. Preserve the uppercase + tracking convention and the 14px/1.6px button style regardless of substitute.

## Layout

### Spacing System
- **Base unit:** 4px (Tailwind `--spacing: .25rem`).
- **Section rhythm:** `--spacing-sections-desktop: 72px`, `--spacing-sections-mobile: 50px` — a tighter rhythm than typical e-commerce (80–100px) so full-bleed hero images follow each other quickly.
- **Grid gutters:** `--grid-desktop-horizontal-spacing: 32px` and `--grid-desktop-vertical-spacing: 32px` — uniform, generous gutters between product tiles; mobile horizontal gap is also 32px.
- **Header gutter:** `2rem` (32px) horizontal padding on the `.header.page-width` and utility bar.
- **Card internal padding:** product-card meta uses `.card__information { padding: 1.3rem 1rem }` with `.5rem` gaps between rows; `.card__content` at `1rem`.
- **Button padding:** `.75rem 2rem` (12px × 32px); `--button--primary--large: 1.19rem 2rem`.
- **Cart drawer:** `.drawer__inner` 525px wide desktop, 100% width mobile; `.drawer__footer` 24px padding.

### Grid & Container
- **Max content width:** `--page-width: 160rem` (~1600px) — an unusually wide rail for a storefront, favoring large product imagery.
- **Product grids:** Dawn `.grid` with 2-up mobile → 4-up desktop (`.grid--4-col-desktop`), plus horizontal scroll sliders on the homepage rails with `scroll-snap` and a `--desktop-margin-left-first-item` peeking gutter.
- **Collection page:** full-bleed hero image (2:3 mobile → 27:14 desktop) with the H1 + uppercase kicker overlaid, then the product grid.
- **Homepage structure:** full-bleed hero slideshow (3:4 mobile, 16:9 / 21:9 desktop) → per-drop section bands (each: kicker overline + 900-weight title + SHOP button over full-bleed photo) → New Arrivals slider rail → category image cards → TheROCKER rail → technology/category tiles → newsletter band → value-prop row → black footer.
- **Footer:** black band with the SATISFY logo, mission line, and 3 link columns (Shop / Help / Shipping To) plus social icons.

### Whitespace Philosophy
Big, confident, and image-first. Whitespace is generous between full-bleed section bands (72px) but product grids are dense with 32px gutters. Text blocks stay tight and left-aligned (or centered in the small `.banner__box` overlays); there is no airy magazine-style centering — the brand's whitespace reads as deliberate negative space around product photography, not as breathing room for prose.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 — Flat | No border, no shadow | The default for literally every surface — media, product cards, buttons, inputs, popups, drawers, text boxes (`--*-shadow-opacity: 0.0`) |
| 1 — Hairline rule | 1px `rgba(0,0,0,.08)` | Header bottom rule, drawer `details` rows, table separators |
| 2 — Focus outline | 2px `rgba(0,0,0,.5)` outline, offset | Localization selects; card-link focus halo `rgba(0,0,0,.3)` |
| 3 — Modal scrim | Fixed overlay at `rgba(foreground, .5)` | Country selector sheet on mobile (`country-selector__overlay`) |

SATISFY has effectively **no drop-shadow elevation**. Every theme shadow variable is `0.0`; the only "lift" signals are the 50%-opacity scrim over the country/language selector and the focus outline. Depth is entirely manufactured from:
- **Photography** — full-bleed, high-contrast, often textured (dirt, trails, concrete) campaign imagery.
- **Black/white banding** — alternating white content, black footer/menu, dark hero overlays.
- **Product hover image swap** — the card's front photo cross-fades to the back image (`media--hover-effect`), the system's substitute for a shadow-based hover state.

## Components

### Buttons

**`button-primary`** — black fill, white text, `{rounded.sm}` (6px), padding `12px 32px`, label in `{typography.button}` (14px / uppercase / 1.6px tracking), font family Walter. The only CTA on light pages ("Add to Bag", "Subscribe", "SHOP"). Border is 1px solid with full opacity.

**`button-inverse`** — on dark schemes (`color-scheme-4/5`) the button flips to white fill with black text — used on the black footer's newsletter and dark collection CTAs.

**`button-pill`** — a compact pill (`--button--pill`: `1rem` radius, `.44rem 1.44rem` padding) used for small utility actions.

**`button-tertiary` / text link** — `1.2rem` type, `1rem 1.5rem` padding, min-height `3.5rem`, no surface; used for "View all", "Continue shopping", drawer close.

### Navigation

**`top-nav`** — white surface, 32px side padding, logo centered (`.header__heading-link .h2`), left "Shop" disclosure, right account/cart cluster, 1px `rgba(0,0,0,.08)` bottom rule. Wordmark logo rendered as an image at ~19–25px height.

**`announcement-bar`** — the full-width strip "FREE SHIPPING ABOVE 200 USD. FREE RETURNS." in uppercase tracked Simon Mono, centered, single announcement.

**`mega-menu`** — white full-width panel under "Shop" with 4 link columns (Shop / Apparel / Accessories / Footwear / More) in uppercase 12px nav type plus large 900-weight image-CTA cards ("NEW ARRIVALS", "FINAL HEAT", "DESERT RATS", "Foundations", "Women's", "MothTech™") whose titles run at `min(1.75vw, 25px)` weight 900 over photography. Mobile menu is a full-screen drawer with accordion `details` rows divided by `.2` hairlines.

### Cards & Product Surfaces

**`product-card`** — transparent surface, `{rounded.none}` media, **center-aligned** text block. Structure: square-ish gallery image (front/back swap on hover), a row of circular color-swatch links (12px), product name in Simon Mono 14px, price in Simon Mono 14px with 1.6px tracking. "NEW" tag renders as an uppercase badge pill. No card border, no shadow, no padding around media.

**`product-card-swatch`** — 12px circle (`border-radius: 6.25rem`, i.e. 100px) with a 1px `#b6b6b6` ring, clickable through to the color variant.

**`collection-hero`** — full-bleed campaign image with overlay copy: uppercase kicker (e.g., "EMBRACE THE SEASON") + "Collection: New Arrivals" H1 in Walter, aligned center within a `.banner__box` (desktop height ~56rem, aspect 27:14).

**`cart-drawer`** — right-hand drawer, white, 525px, `{rounded.none}`, threshold progress bar (`#b6b6b6` track → `#000000` fill, 4px tall, 25px radius), product list with `.75rem` media cells, and a "Most Popular Gear" rail.

### Forms

**`text-input`** — white, `{rounded.xs}` (5px), 1px border at 55% opacity, height ~56px. Newsletter field (email) with a right-aligned subscribe button. Focus replaces the ring with a 2px black outline (`outline: .2rem solid rgba(foreground, .5)`).

**Variant pills** — size selectors styled as bordered pills (`--variant-pills-radius: 5px`, 55% border opacity), uppercase labels.

### Footer

**`footer-dark`** — black surface, white text in Simon Mono. Layout: centered wordmark image → mission line ("Since launching in 2015, SATISFY® develops technical equipment that reduces distractions to help runners unlock the High.") → 3 columns (Shop / Help / Shipping To) with uppercase headings → social row (Instagram, Strava, YouTube icons) → legal line ("©2026 SATISFY®") + cookie/terms/privacy links.

## Responsive Behavior

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 750px | Header collapses to hamburger + centered logo + cart; hero slideshow 3:4; product grids 2-up; collection hero 2:3; section padding drops to 50px; country selector becomes a full-screen bottom sheet over a 50% scrim; cart drawer goes full-width |
| Tablet / small desktop | 750–989px | Grids stay 2-up; sliders scroll with snap; hero 21:9–16:9 |
| Desktop | ≥ 990px | Full nav with mega-menu; product grids 4-up; cart drawer fixed 525px; hero slideshow full-viewport-height (`100dvh`); PDP gallery side-by-side with sticky buy box |
| Wide | > 1400px | Content rail holds at ~1600px (`--page-width`); sliders use the peek-gutter alignment |

### Touch Targets
- Primary CTA `min-height: 2rem + 2px` base, padded to ~48px effective; `button--primary--large` taller.
- Slider orbs 50px circular (`3.125rem`) on `gray-90`.
- Cart-quantity steppers and icon buttons at 44px (`.slider-button` 44×44) and 32px (`.cart-slider-button`).
- Disclosure rows and mobile filter labels at 40px height.

### Collapsing Strategy
- Desktop mega-menu → mobile full-screen accordion drawer.
- Product sliders snap horizontally instead of reflowing to columns on tablet.
- Collection hero aspect flips 27:14 → 2:3 with the same overlay text.
- The cart drawer and country selector convert to full-viewport bottom sheets below 750px.
- Hero text overlays stack (kicker → title → button) rather than horizontally splitting.

## Do's and Don'ts

### Do
- Set body copy in `ABC Simon Mono` (fallback IBM Plex Mono) and every headline in `ABC Walter Neue` Extrafett (900). There is no other acceptable display voice.
- Default to **uppercase + wide tracking** for buttons (14px / 1.6px), nav links, kicker overlines (16px / 2.08px), and unit prices (11px / 0.64px).
- Keep surfaces **flat and shadow-free** — the theme pins every shadow variable to `0.0`. Use photography and black/white banding for depth, never drop shadows.
- Use `{rounded.none}` (0px) on product media and gallery imagery; keep the machinery soft but restrained — 6px buttons, 5px inputs, 16px pills, 100px circles for swatches and orbs.
- Reserve accent hues (`#f7e37e`, `#dcdb7d`, `#79b884`, `#5c6e7c`, `#897f98`, `#baafa4`) for full-bleed section washes and per-drop schemes only. Mainline chrome is black and white.
- Present product names in Simon Mono at 14px with tracking, centered under the image, with color swatches as circular 12px links.
- Build hierarchy from weight (400 mono vs 900 grotesque) and uppercase treatment, not from color or grey-scale text.

### Don't
- Don't introduce a rounded product card or gallery media — the hard 0px corner is a brand signal.
- Don't add a light-weight heading or a serif anywhere in mainline commerce chrome.
- Don't use grey as a text color; secondary emphasis is expressed via opacity on black, not grey hexes.
- Don't place the accent yellow/lime/green hues as decorative buttons or icons on white — they are scheme washes.
- Don't use sentence case for nav, buttons, or section kickers — the system is uppercase-first.
- Don't break the 32px product-grid gutter or the 72px/50px section rhythm.
- Don't ship a modal/drawer with a drop shadow — the system's only overlay depth is the 50%-opacity scrim.

## Known Gaps

- **Mobile-only chrome** was not rendered in this extraction; the responsive behaviors above synthesize the theme's media-query CSS (750px / 990px) rather than photographed mobile layouts.
- **Exact hero-kicker font sizes** for each homepage band are not individually pinned in the stylesheet — the observable classes are `--text-overline-xs: 10px`, `.caption-with-letter-spacing: 16px`, and the Tailwind `text-overline-xs` / `text-sub1` tokens; per-band overrides in section JSON were not accessible.
- **The "Possessed" magazine surfaces** (`/collections/objects`) and the Pro Team page were not extracted; the h2-possessed type tokens (38px/40px) suggest a distinct editorial treatment (likely italic Walter) not captured here.
- **Form validation states** (error text, success, inline help) are not documented — no validated forms were present in the captured pages.
- **Semantic error/success colors** could not be extracted; the theme exposes none in the served color schemes.
- **Login / account surfaces** (Shopify customer flows) are not in the captured set.
- **Cart drawer "Most Popular Gear" rail and dynamic PDP 360 spins** depend on JS-rendered content; their exact type/radius values were inferred from shared tokens.
- **A few hex values** in the served CSS (`#807ea3` in `main.css`) suggest additional scheme variants not tied to an observed page region.
