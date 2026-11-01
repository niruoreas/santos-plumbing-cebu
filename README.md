# Santos Plumbing, Cebu City

**Live:** https://santos-plumbing-cebu.vercel.app

A one-page website for a plumber in Cebu City, built with Claude Code.

## What's on the page

- **Hero** with the headline, a short line about the business, a big **Call now** button (`tel:+639000000000`) and a **Message on WhatsApp** button
- **Three services:** Leak repair, Drain cleaning, Water heater. Each card has its own call link.
- **Areas** around Cebu City, with a nudge to send a barangay on WhatsApp
- **Closing call-to-action** with a second Call now button
- **Floating WhatsApp button** that stays in reach while scrolling
- **Footer:** "Built by Nyl Bhoy Oreas"

## Built for phones and speed

- Designed at 390px first, then scaled up for tablet and desktop
- One HTML file of about 13 KB. CSS is inline, icons are inline SVG, and there are no web fonts, images or JavaScript, so the page loads in a single request.
- Tap targets are at least 48px, there's no sideways scrolling from 320px to 1920px, and keyboard focus and reduced motion are supported

## Run it

Open `index.html` in a browser. Nothing to install.

`CLAUDE.md` has the project rules used when working on this with Claude Code.
