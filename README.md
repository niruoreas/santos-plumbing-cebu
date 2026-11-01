# Santos Plumbing, Cebu City

**Live:** https://santos-plumbing-cebu.vercel.app

A one-page website for a plumber in Cebu City, built with Claude Code.

## What's on the page

- **Hero** that asks in Bisaya ("Nagtulo? Barado? Bugnaw ang shower?"), a short line in English, a big ringing **Call now** button (`tel:+639000000000`) and a **WhatsApp** button. A drawn faucet drips into a ripple, and a wave moves along the bottom.
- **Three services on one pipe:** Leak repair, Drain cleaning, Water heater. Water flows down a pipe that links the three cards, each with its own call link.
- **WhatsApp chat preview:** "Send a photo. Get a price.", with a button to start the chat
- **Moving strip of barangays** around Cebu City
- **"Call us now." closing** with a second Call now button
- **Floating WhatsApp button** that stays in reach while scrolling
- **Footer:** "Built by Nyl Bhoy Oreas"

## Built for phones and speed

- Designed at 390px first, then scaled up for tablet and desktop
- One HTML file (about 25 KB, roughly 6 KB gzipped). CSS is inline, the faucet, waves and icons are inline SVG animated with CSS, and there are no web fonts, images or JavaScript, so the page loads in a single request.
- Tap targets are at least 48px, there's no sideways scrolling from 320px to 1920px, and keyboard focus is visible, and every animation switches off for people who prefer reduced motion

## Run it

Open `index.html` in a browser. Nothing to install.

`CLAUDE.md` has the project rules used when working on this with Claude Code.
