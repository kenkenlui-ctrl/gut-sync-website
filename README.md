# Gut Sync · Corporate Homepage

Bilingual landing page for **Gut Sync** (gut-sync.com) and its flagship product **Sync AI Temple** — an AI + Chinese metaphysics platform (擇日 / 命理 / 風水 / 祈福).

## Stack

- Pure static HTML + CSS + JS — **no build step**
- Vanilla CSS with custom properties (no frameworks)
- Google Fonts (Cormorant Garamond, Noto Serif/Sans TC, Ma Shan Zheng, Inter)
- Total payload: ~2.6 MB (hero image 318 KB, 6 section images, 4 team photos)

## Files

| Path | Purpose |
|---|---|
| `index.html` | Single-page site (28 KB) — Hero / Features / App / Vision / Team / CTA |
| `imgs/` | Hero + 4 capability tiles + vision background (6 JPGs) |
| `team-photos/` | 4 founder portraits (Carine, Match, Calvin, Kenneth) |
| `README.md` | This file |

## Deploy to gut-sync.com

This repo is the **single source of truth**. Pick whichever host the friend prefers:

### Cloudflare Pages (recommended)
1. https://dash.cloudflare.com → Workers & Pages → Create application → Pages → Upload assets
2. Project name: `gut-sync`
3. Drag this entire folder (or the unzipped contents) → Deploy
4. Custom domains → Set up a custom domain → `gut-sync.com`
5. At the domain registrar (GoDaddy / Namecheap / etc.), add the CNAME record Cloudflare shows

### Vercel
1. https://vercel.com → New Project → Import `kenkenlui-ctrl/gut-sync-website`
2. Vercel auto-detects static site. Click Deploy.
3. Project Settings → Domains → Add `gut-sync.com`
4. At domain registrar, add the A/CNAME record Vercel shows

### Netlify
1. https://app.netlify.com → Add new site → Deploy manually → drag this folder
2. Domain settings → Add `gut-sync.com`

## Editing content

- All copy + section structure lives in `index.html` (single file)
- Replace team photos in `team-photos/` (keep filename the same: `carine.jpg`, `match.jpg`, `calvin.jpg`, `kenneth.jpg`)
- Replace hero/section images in `imgs/` (keep filenames the same)
- Re-deploy after changes

## Contact

hello@gut-sync.com · Hong Kong · A SyncBuddy Tech Limited Initiative

