# kristagraham.art

Portfolio site for Krista Graham — painter & tattoo artist, Phoenix AZ.

## Structure
- `index.html` — the whole site (single page)
- `images/` — all artwork images (`work-*`, `mural-*`, `img-*`)
- `netlify.toml` — tells Netlify to publish the root folder as-is

## Editing
Open `index.html`. The gallery is driven by the `WORKS` and `MURALS`
arrays near the bottom of the file; each entry points at a file in `images/`.
To add a piece: drop the image in `images/`, add an entry to the array.

## Deploy
Push to GitHub. In Netlify, link this repo to the **kristagraham-art**
site (Site configuration → Build & deploy → Link repository). Every push
to `main` then deploys automatically. No build command; publish dir is `.`.
