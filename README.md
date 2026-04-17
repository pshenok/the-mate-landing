# the-mate-landing

Marketing landing page for **TheMate** — an AI voice teammate that answers every call 24/7, captures leads, books appointments, and escalates emergencies.

## Stack

Single-file static site:

- `index.html` — all markup, styles and JS
- Tailwind CSS via CDN (`cdn.tailwindcss.com`)
- Inter font via Google Fonts
- No build step, no dependencies

## Run locally

```sh
python3 -m http.server 4173
# open http://localhost:4173
```

## Deploy

Any static host works: GitHub Pages, Cloudflare Pages, Netlify, Vercel, S3, etc. Just serve `index.html`.
