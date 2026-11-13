# Yard Sale

A simple, static yard sale website. No name, no tracking, no build step.

## Files
- `index.html` — the page (Moving to Alaska sale: Sat Nov 14 & Sun Nov 15, 8 AM – 2 PM, 1132 N. Fairville Ave, Harrisburg)
- `styles.css` — all styling

## Deploy to Cloudflare Pages
1. Go to Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git
2. Select this repository (`yard-sale`)
3. Build settings:
   - Framework preset: **None**
   - Build command: *(leave empty)*
   - Build output directory: `/`
4. Save and Deploy — Cloudflare will give it a `*.pages.dev` address, and it will redeploy automatically on every push to `main`.

## Updating the sale details
Edit the "When / Where / Payment" section in `index.html`, commit, and push. Cloudflare redeploys automatically.
