# MA in Translation, NKUA — public site

Single-file static site for the MA in Translation (Translation Studies specialization), 2026-2028 cycle.

Live URL once deployed: **https://ma-ling-enl-uoa.github.io/ma-translation-2026/**

## Deploy on GitHub Pages (one-off, ~5 minutes)

1. Sign in to GitHub. If `ma-ling-enl-uoa` does not yet exist, create it as either a personal account or, preferably, a free GitHub **organisation** (Settings → Organisations → New).
2. Create a new public repository under that account named exactly **`ma-translation-2026`**. Do not add a README or .gitignore at creation; just create it empty.
3. Upload the contents of this folder. Easiest path:
   - On the empty repo page, click **Add file → Upload files**.
   - Drag `index.html` and `README.md` from this folder into the upload area.
   - Commit straight to `main`.
4. Enable GitHub Pages:
   - Repo → **Settings → Pages**.
   - **Source:** Deploy from a branch.
   - **Branch:** `main`, folder `/ (root)`. Save.
5. Wait 30-60 seconds. The site is live at:
   - `https://ma-ling-enl-uoa.github.io/ma-translation-2026/`

## Updating the site later

Edit `index.html` directly on GitHub (pencil icon → Commit changes) or push a new version. Pages re-deploys automatically within a minute.

## File contents

- `index.html` — the entire site, single file, no external dependencies except Google Fonts (loaded via CDN).
- `README.md` — this file.

## Custom domain (optional, later)

If NKUA IT can give you a subdomain (e.g. `mat.enl.uoa.gr`):

1. Ask IT to add a CNAME DNS record `mat.enl.uoa.gr → ma-ling-enl-uoa.github.io`.
2. In repo Settings → Pages → Custom domain, enter `mat.enl.uoa.gr` and save.
3. Tick "Enforce HTTPS" once the certificate provisions.
