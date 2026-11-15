# royeaa's gallery — Nidha's portfolio

`index.html` is the whole site: styles, scripts and all 11 sketches are built in, so it works on its own.

## Deploy on Vercel
1. Push this folder to a GitHub repo (or drag the folder into vercel.com/new).
2. Framework preset: **Other**. No build command, no output directory.
3. Deploy. `index.html` is served at the root.

## Edit Nidha's details
Open `index.html`, find `const CONFIG = {` near the bottom, and change:
- `photo` – link to her photo (or a data: URL)
- `email` – contact form sends here when set; otherwise it opens Instagram
- `location`, `heroLine`, `bio1`, `bio2`, `introText`
- `paper` – sketch paper size shown in the detail view

Sketch titles and descriptions are in the `SKETCHES` list just below CONFIG.

The `sketches/` folder holds the cleaned sketch images separately, in case you need them elsewhere.
