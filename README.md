# AshleyAdamsBeauty.com — Quick Launch

This folder contains your ready-to-publish website for **The A+ Experience**.

## 1) Buy your domain
- Registrar options: Namecheap, Google Domains (via Squarespace), GoDaddy, Cloudflare, Porkbun.
- Domain: **AshleyAdamsBeauty.com**

## 2) Pick a host (easy options)
- **Squarespace / Wix** (all‑in‑one, drag‑and‑drop)
- **Netlify** (free static hosting, very fast)
- **GitHub Pages** (free, simple)

## 3) Point the domain to your host

### If using Squarespace
1. In Squarespace: **Settings → Domains → Use a domain I own** → enter `AshleyAdamsBeauty.com`.
2. Squarespace gives you DNS records. Copy them into your registrar (A and CNAME records).
3. Wait for DNS to propagate (usually 5–30 minutes).

### If using Netlify
1. Create a Netlify site and **drag this folder** onto Netlify (or upload the ZIP).
2. In Netlify: **Site settings → Domain management → Add custom domain** → `AshleyAdamsBeauty.com`.
3. Netlify will give you nameservers or records. Easiest: use **Netlify DNS** and set your registrar’s nameservers to Netlify.

### If using GitHub Pages
1. Create a repo and upload these files.
2. In repo **Settings → Pages**: choose **main / root**.
3. In **Pages → Custom domain**: enter `AshleyAdamsBeauty.com`.
4. In your registrar DNS, add a `CNAME` record for the root: `AshleyAdamsBeauty.com` → `AshleyAdamsBeauty.com` and/or A records per GitHub’s docs.

## 4) Update links
- In `index.html`, the **Book Now** button dials: `901‑547‑5218`.
- Update the Facebook link in the Contact section when you’re ready.

## 5) Add your portfolio photos
- Put your real images into `assets/` and replace the placeholders in the **Gallery** section.

## 6) Optional email at your domain
- Create: `hello@AshleyAdamsBeauty.com` (via Google Workspace or your host’s mail).
- Update the **Email** button in the Contact section.

— Generated 2025-10-06
