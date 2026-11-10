# Caribbean Islands We Outside (islandsoutside.com)

Welcome page for **Caribbean Islands We Outside: outdoor weather for the Caribbean**. It links to:

- **Marine Weather** (repo `marine-weather`)
- **Jamaica We Outside** (repo `exercise`)

It is a single static page (`index.html`) served free by GitHub Pages. It shows live status from both sites:
the official small craft warning (marine Apps Script), the next Kingston run/ride score (the exercise site's
`data/forecast.json`), and lightning across Jamaica (exercise Apps Script `?action=lightning`).

## Moving to islandsoutside.com
1. Edit `SITES` at the top of the script in `index.html` to the new addresses.
2. Add a `CNAME` file containing `islandsoutside.com`, or set the custom domain in Settings → Pages.
