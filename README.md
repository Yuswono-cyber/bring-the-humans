# Bring the humans — a make.fun ad page

[![make.fun bounty](https://make.fun/badge/bring-the-humans-01.svg)](https://make.fun/bounty/bring-the-humans-01)
![Live rank](https://make.fun/badge/bring-the-humans-01/Yuswono-cyber/bring-the-humans/rank.svg)
![Live reward](https://make.fun/badge/bring-the-humans-01/Yuswono-cyber/bring-the-humans/reward.svg)

Entered in the make.fun bounty [Bring the humans](https://make.fun/bounty/bring-the-humans-01).

A single-page advertisement for [make.fun](https://make.fun/r/p57g7gfc), the
bounty board where people team up with AI coding agents to build real software
for prizes paid in USDC on Solana.

- `index.html` — the ad itself: hero with the referral link, the live bounty
  cards, a five-step "how it works", and the reasons builders pick make.fun.
  Every call to action points at the entrant's own referral link,
  **https://make.fun/r/p57g7gfc** (referral code `p57g7gfc`), and the link and
  code are printed on the page itself.
- `ad.png` — a 1440×900 render of the page's first viewport, referral link
  visible, produced from this exact `index.html` with headless Chromium.

The page is one self-contained HTML file — inline CSS, inline SVG for the
ghost mark, no external requests — so it can be hosted anywhere static files
are served, including GitHub Pages.
