# CLAUDE.md

Rules for working on this repo. Read before changing anything.

## What this is

A one-page website for **Santos Plumbing, Cebu City**. Everything lives in `index.html`: the HTML, with the CSS in a single `<style>` block. There's no JavaScript, no framework and no build step.

## Must keep

- The hero has a headline, a short paragraph and a big **Call now** button linking to `tel:+639000000000`.
- Three services: **Leak repair**, **Drain cleaning**, **Water heater**.
- A WhatsApp button (`https://wa.me/639000000000`): one in the hero and a floating one bottom right.
- The footer says `Built by Nyl Bhoy Oreas`.
- Phone numbers stay in international format (`+63`) so they work from any phone.

## Speed rules

- One request for the page. Keep CSS inline and icons as inline SVG.
- No web fonts (system font stack only), no images, no external scripts. If an image is ever added, use WebP or AVIF, give it width and height, and lazy-load anything below the fold.
- Keep `index.html` under about 20 KB.

## Mobile rules (390px is the main target)

- Design for the phone first. Desktop changes go inside `@media(min-width:720px)`.
- Every tap target is at least 48px tall. The Call now button is the biggest thing on the screen.
- No sideways scrolling from 320px to 1920px.
- Nothing important sits under the floating WhatsApp button. The footer has extra bottom padding for it, so keep that.
- Respect `prefers-reduced-motion` and keep a visible `:focus-visible` outline.

## Copy

Short, plain and local. Say what we fix and how to reach us. No slogans or filler, and don't make claims the business hasn't confirmed (licences, years in business, prices).

## Before calling a change done

1. Check at 390px first, then 320, 375, 430, 768, 1024, 1440 and 1920px.
2. Every `tel:` and WhatsApp link points to the numbers above.
3. "Built by Nyl Bhoy Oreas" is visible in the footer and not covered by the WhatsApp button.
