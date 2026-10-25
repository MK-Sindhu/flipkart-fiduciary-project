# Fiduciary

Your agent knows your habits. Fiduciary protects your goals.

A product concept for 2040: an independent, user-paid check between a person and their AI agent. It can't buy, book, send or sign. It only reads, checks, holds and asks.

- **Website:** [fiduciary.ndstill.com](https://fiduciary.ndstill.com)
- **Live demo:** [fiduciary.ndstill.com/app](https://fiduciary.ndstill.com/app/), a single-file HTML/CSS/JS prototype that also runs offline

Built for the Flipkart APM '29 case submission.

## Structure

```
index.html        landing page
app/index.html    interactive prototype (self-contained, works offline)
assets/site.css   design system + site styles
assets/fonts/     Bricolage Grotesque and Figtree (SIL Open Font License), subset
vercel.json       static hosting config
```

Plain HTML, CSS and JS: no framework and no build step. To run locally, open `index.html` in a browser.

## Deploy

Import this repo in Vercel as a static site (framework preset **Other**, no build command, output directory `.`), then add the domain `fiduciary.ndstill.com` under Project → Settings → Domains.
