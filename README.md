# getfinalform-site

Marketing site for FinalForm, deployed on Cloudflare Pages at
**getfinalform.com**.

A static Astro site presenting FinalForm's products — currently featuring
**MyLittleGymBro** (the app itself lives at `mylittlegymbro.getfinalform.com`).

## Tech

- [Astro](https://astro.build) (static output, no adapter needed)
- Brand palette: purple `#3100e0` primary, cream surfaces — matches the
  MyLittleGymBro design system
- Inter typeface

## Local development

```bash
npm install
npm run dev      # start the dev server
npm run build    # build static site to dist/
npm run preview  # preview the production build
```

## Deploying to Cloudflare Pages

The build output is static (`dist/`). Two options:

### Option A — Cloudflare Pages dashboard

1. In Cloudflare, create a **Pages** project connected to your git repo.
2. Framework preset: **Astro**.
3. Build command: `npm run build`
4. Build output directory: `dist`
5. Add a **custom domain**: `getfinalform.com`.

### Option B — Wrangler CLI

```bash
npm install -D wrangler
npx wrangler pages deploy dist          # one-off deploy
npx wrangler pages deploy dist --project-name getfinalform-site
```

`wrangler.toml` is configured with `pages_build_output_dir = "dist"` and the
project name.

## Pages

- `/` — home
- `/products/` — product overview
- `/products/mylittlegymbro/` — MyLittleGymBro product page
- `/about/` — about FinalForm
- `/404.html` — not found

## TODO

- Add a real 1200×630 `public/og.png` for social link cards (referenced by the
  layout's default Open Graph image).
