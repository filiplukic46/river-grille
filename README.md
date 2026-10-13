# River Grille — Website

Static one-page site for River Grille (Chatham, NJ). No build step.

## Files
- `index.html` — the site
- `support.js` — runtime (required, keep next to index.html)
- `assets/` — logo + photos
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Deploy to GitHub Pages
1. Create a new repository and upload the contents of this folder to its root.
2. In the repo: **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, pick `main` and `/ (root)`, save.
4. Wait ~1 minute — the site goes live at `https://<username>.github.io/<repo>/`.

### Local preview
Open a terminal in this folder and run any static server, e.g.:
```
python3 -m http.server 8000
```
Then visit http://localhost:8000. (Opening `index.html` directly via `file://` may block the fonts/scripts — use a server.)

## Notes
- Requires an internet connection for Google Fonts and the embedded Google map.
- Placeholder links: "Order Online" / menu point to chathamrivergrille.com; reservation and some event links are `#` anchors — swap in real URLs when available.
