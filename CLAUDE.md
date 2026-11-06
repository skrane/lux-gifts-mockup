# LuxGiftsnGoods redesign mockup: working notes for Claude

Steven manages his projects by talking to Claude in plain English. He is not a developer
and does not use git directly. When he asks for a change, do the whole thing: edit, commit,
push to `main`, then confirm in plain language what he will see. Never use em-dashes in
anything written for him.

## What this is

A one-file website redesign mockup (`index.html`) for luxgiftsngoods.com, a Nashville gift
retailer (WordPress/WooCommerce today, founder Michael J. Mills). It is marked noindex and is
for review only, not a live site. Nothing is really for sale: the cart, gift finder, quick
view and checkout all work in the browser only, and prices are placeholders.

- Repo: https://github.com/skrane/lux-gifts-mockup
- Preview locally: `cd ~/Projects/lux-gifts-mockup && python3 -m http.server 8787` then
  open http://localhost:8787/ in Chrome.

## Design decisions

- Kept the brand DNA of the current site: green monogram mark (LG/nG) and plum wordmark,
  tagline "Luxury Gifts for Every Celebration". Added gold as an accent.
- Fonts: Cormorant Garamond (headings) and Inter (body), loaded from Google Fonts.
- Navigation is by recipient and occasion instead of the old 150-link brand menu.
- Policies shown in the mockup (30-day returns, free gift wrap, free shipping over $99) are
  recommendations, not the store's current policies. Flag this if Steven shares it with
  the owner.
