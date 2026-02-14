# DOIN Website

Homepage for the Decentralized Optimization and Inference Network.

## Deploy

This site is deployed via GitHub Pages from the `main` branch root.

### Setup
1. Push this repo to `harveybc/doin-site` (or `harveybc/doin.network`)
2. Go to Settings → Pages → Source: Deploy from branch → `main` / `/ (root)`
3. (Optional) Add custom domain: `doin.network` in Settings → Pages → Custom domain
4. DNS: Add a CNAME record pointing `doin.network` → `harveybc.github.io`

### Local preview
```bash
python3 -m http.server 8765
# Open http://localhost:8765
```
