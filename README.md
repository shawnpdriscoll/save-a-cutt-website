# Save-A-Cutt! Website

A single-page site for Orris Lurry, Jr.'s lawn & landscape business, built to deploy free on GitHub Pages. No build tools needed — it's plain HTML/CSS/JS.

## Files
- `index.html` — the page content
- `styles.css` — all styling (palette, fonts, hedge/palm/flower decorations)
- `script.js` — mobile menu, scroll animations, footer year

## Publish it on GitHub Pages (free)

1. Go to [github.com](https://github.com) and log in (or create a free account).
2. Click the **+** in the top right → **New repository**.
   - Name it something like `save-a-cutt-website` (or `<your-username>.github.io` if you want it as your main GitHub site).
   - Set it to **Public**.
   - Don't add a README — you already have one.
3. On the new repo page, click **uploading an existing file**, then drag in `index.html`, `styles.css`, and `script.js` (and this README if you like). Commit the changes.
4. Go to the repo's **Settings** tab → **Pages** (left sidebar).
5. Under "Build and deployment" → **Source**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
6. GitHub will give you a live URL after a minute or two, usually:
   `https://<your-username>.github.io/save-a-cutt-website/`

That's it — no server, no cost. Any time you want to update text or a phone number, edit the file on GitHub (pencil icon) and commit; the live site updates automatically within a minute.

## Making changes later
- **Phone/email/license**: search for them in `index.html` (they appear in the hero, contact section, and footer) and replace.
- **Colors**: all defined once at the top of `styles.css` under `:root` — change a hex value there and it updates everywhere.
- **Adding a real photo**: replace the "OL" monogram badge in the About section with an `<img>` tag once you have a photo of Orris or the crew.
