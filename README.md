# Vy Rentals — GitHub Pages Files (no zip)

Upload these three files to the **root** of your GitHub repo (branch: `main`), then turn on **GitHub Pages**.

## Files
- `index.html` — your site
- `.nojekyll` — disables Jekyll processing (ensures plain file serving)
- `CNAME` — sets custom domain to **www.vy-rentals.com**

## Publish steps
1) Create a public repo (e.g., `vy-rentals-site`).
2) **Add file → Upload files** → drag **index.html**, **.nojekyll**, and **CNAME**.
3) Repo **Settings → Pages** → **Deploy from a branch** → **main** / **/(root)** → **Save**.
4) In the same Pages screen, set **Custom domain** to `www.vy-rentals.com` and check **Enforce HTTPS** once available.

## DNS (Cloudflare)
- **CNAME** `www` → `<your-username>.github.io` (DNS only / gray cloud).
- (Optional) Apex: either add the four GitHub A records (185.199.108.153, .109.153, .110.153, .111.153) **or** create a redirect rule `vy-rentals.com` → `https://www.vy-rentals.com`.

_Last updated: 2025-10-07_
