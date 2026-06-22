# Sellvia — Free Store + 5-in-1 Turbo Sales Bundle

Landing page for Sellvia's lead offer: a **free, ready-made online store** plus a
**5-in-1 Turbo Sales Bundle** (normally **$1,899**, free with the store).

The page is a clone of the live Sellvia design at
<https://sellvia.com/free-online-store-plus-sales-on-autopilot/> (the "Apple design
system" layout, SF Pro Display webfont), with the copy replaced by the Turbo Sales
Bundle offer from `sellvia-turbo-sales-bundle (4).html`.

## The offer — what's in the bundle

1. **Turnkey online store** — fully hosted, custom domain, SSL, 100+ products pre-loaded.
2. **$40 ad credit** — first ad campaign across Amazon, Google, Facebook, TikTok & Instagram is on us.
3. **Free Google Promo** — SEO blog articles built to rank on Google for free organic traffic.
4. **7 AI Influencers** — AI creators make promo videos for TikTok/Instagram (free for 14 days).
5. **Personal growth manager** — a real person who guides launch and growth.

Headline: **"Get a free store with a Turbo Sales Bundle on top."**
CTA target: `https://sellvia.com/checkout/?product=custom&type_custom=free_basic_hosting`

## Files

- **`index.html`** — self-contained landing page. Open directly in a browser to preview.
  All CSS/JS is inline. Fonts are local (`fonts/sfpro/`); images load from `sellvia.com`.
- **`fonts/sfpro/`** — SF Pro Display webfont (woff2) + `style.min.css`.

## Page structure

Topbar → nav → **hero** (Turbo Sales Bundle headline) → stat bar →
**Step 1: your free store** → **Step 2: 5-in-1 Turbo Sales Bundle** (animated bento:
AI Influencers · $40 ad credit · automated · Free Google Promo) → how it works (3 steps) →
what's included → product catalog → awards / ratings / testimonials → FAQ (accordion) →
final CTA → footer.

## Status — iterative copy pass

First pass applied: title/meta, topbar, nav, hero, all CTAs ("+ Turbo Pack"), the Step 2
bundle section, the three bento cards, how-it-works, key FAQ answers, and the final CTA.

Still open to refine ("по ходу" / as we go):

- Optionally rebuild the Step 2 bento into 5 explicit tool cards (one per bundle item).
- Spotlight `$40 ad credit` / `Free Google Promo` / `7 AI Influencers` in the "What do I get" tiles.
- Add the dedicated "auto-promotion — also available" section and more Turbo-specific FAQ items.
- Optionally localize images (currently served from `sellvia.com`).

## Source

- Offer copy & meaning: `sellvia-turbo-sales-bundle (4).html`
- Design / structure / fonts: <https://sellvia.com/free-online-store-plus-sales-on-autopilot/>
