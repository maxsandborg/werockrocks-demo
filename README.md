# Zellyfi Demo Hub

Client demo websites built by [Zellyfi](https://zellyfi.com). Each subfolder is a standalone demo site for a client.

> **Note:** This repo was originally named `werockrocks-demo`. Consider renaming to `zellyfidemo` in GitHub Settings → General → Repository name.

## Live

[www.zellyfidemo.com](https://www.zellyfidemo.com)

## Demos

| Client | Path | Description |
|--------|------|-------------|
| We Rock Rocks | [/werockrocks](https://www.zellyfidemo.com/werockrocks) | Crystal, mineral & gemstone shop — Tampa Bay, FL |
| Exotic Smokes | [/exoticsmokes](https://www.zellyfidemo.com/exoticsmokes) | 24/7 smoke shop, hookah lounge & kava bar — 3 locations |

## Structure

```
index.html              # Demo hub landing page
werockrocks/            # We Rock Rocks demo
  ├── index.html
  ├── blog.html
  ├── seo-dashboard.html
  ├── robots.txt
  └── sitemap.xml
exoticsmokes/           # Exotic Smokes demo
  └── index.html
vercel.json             # Rewrites & headers for all demos
```

## Adding a New Demo

1. Create a folder: `newclient/index.html`
2. Add rewrites to `vercel.json`
3. Add a card to `index.html` (hub landing page)
4. Push to `main` → auto-deploys to Vercel

## Deploy

Auto-deployed on Vercel with custom domain `www.zellyfidemo.com`. Push to `main` branch to trigger deploy.
