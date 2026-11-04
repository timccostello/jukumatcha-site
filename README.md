# JUKU Matcha

Static landing page for [jukumatcha.com.au](https://jukumatcha.com.au). Plain HTML and CSS, with no build step and no framework.

## Folder structure

- `index.html` is the page.
- `styles.css` is the layout and visual styling.
- `images/` holds the photos and illustrations used on the page. `hero.jpg` is the social share image; the page itself uses `hero.webp`.
- `favicon.ico`, `favicon-32.png`, and `apple-touch-icon.png` are made from the logo.

Buy buttons go to the JUKU Matcha collection on jukuaustralia.com.au, with UTM parameters so orders from this page can be attributed.

## Deploy

The site is hosted on Cloudflare Pages. Pushing to `main` redeploys it.

- Build command: none
- Output directory: `/`

To preview locally, open the folder in a static server (for example `python3 -m http.server`) and visit the printed address. Opening `index.html` directly also works.
