# getfinalform-site

Marketing site for **FinalForm** — an e-commerce wellness brand — deployed on
Cloudflare (Workers static assets) at **getfinalform.com**.

The site is a brand-facing landing page: it captures emails for early access to
FinalForm's free wellness tools. Products are intentionally not listed here;
the e-commerce side lives separately at `supplementstacks.getfinalform.com`.

## Tech

- [Astro](https://astro.build) (static output)
- Design system: Airbnb-inspired — white canvas, Rausch `#ff385c` primary, soft
  corners, Inter typeface
- Deploy: Cloudflare Workers Static Assets (`wrangler.toml` → `[assets]`),
  git-connected via Workers Builds

## Local development

```bash
npm install
npm run dev      # start the dev server (also: astro dev --background)
npm run build    # build static site to dist/
npm run preview  # preview the production build
```

## Pages

- `/` — brand landing + email early-access signup (UI-only for now)
- `/about/` — brand story
- `/legal/` — privacy policy & terms
- `/404.html` — not found

## Signup

The signup form is UI-only in this version: it validates the email and shows a
success message on the client. No data is stored yet. Wire real capture (e.g., a
Cloudflare Worker + D1) before enabling production signups.

## Deploy

Workers Builds (git-connected): set the **Build command** to `npm run build`
and keep the deploy command `npx wrangler deploy`. The build outputs `dist/`,
which `wrangler deploy` serves as static assets. Custom domains:
`getfinalform.com` + `www.getfinalform.com`.

## TODO

- Add a real 1200×630 `public/og.png` for social link cards.
