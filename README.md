# Personal Website

A simple, single-page personal site built with plain HTML, CSS, and JavaScript. No build step — just open `index.html` or deploy the directory as a static site.

## Files

- `index.html` — page structure and content
- `styles.css` — styling, including light/dark themes
- `main.js` — theme toggle and small interactions

## Customize

Open `index.html` and replace the placeholder content:

- Name in the `<title>`, hero (`<h1>`), `.avatar` initials, and footer
- Tagline and About section copy
- The three project cards under `#projects`
- Links under `#contact` (GitHub, Twitter/X, LinkedIn, email)

To change the accent color or fonts, edit the `:root` and `[data-theme="dark"]` variables at the top of `styles.css`.

## Run locally

Just open `index.html` in a browser, or serve the directory:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Drop the directory into any static host — GitHub Pages, Netlify, Vercel, Cloudflare Pages, etc.
