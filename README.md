# Kadena Cafe

Website for Kadena Cafe, a locally owned neighborhood café in Summerville, SC (a branch of Area 51 Foods).

Plain HTML, CSS and a little JavaScript. No build step.

## Files

- `index.html` – the page (menu, about, drinks, hours & visit)
- `styles.css` – all styling and the brand palette (CSS variables at the top)
- `script.js` – mobile menu toggle and active-link highlighting
- `assets/logo.png` – full Kadena Cafe logo (About section)
- `assets/logo-mark.png` – palm/sun/wave crop of the logo (header and favicon)
## Run locally

Open `index.html` in a browser, or serve the folder with any static server, e.g.:

```
npx serve .
```

## Editing content

- **Menu items:** the `.ticket` articles in the `#menu` section of `index.html`.
- **Hours / address / phone / email:** `#visit`, the footer, the nav "Open daily" pill, and the JSON-LD block in `<head>`.
