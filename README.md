# brainfieldllc.com

Static one-page site for BrainField LLC, served by GitHub Pages.

- `index.html` — the whole site (HTML + inline CSS + inline JS, no build step)
- `CNAME` — custom domain for GitHub Pages (`brainfieldllc.com`)

## Deploy

1. Push to `main`.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Settings → Pages → Custom domain: `brainfieldllc.com`, then tick **Enforce HTTPS**
   once the certificate is issued.

## DNS (at the registrar)

| Type  | Name | Value |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| AAAA  | @    | 2606:50c0:8000::153 |
| AAAA  | @    | 2606:50c0:8001::153 |
| AAAA  | @    | 2606:50c0:8002::153 |
| AAAA  | @    | 2606:50c0:8003::153 |
| CNAME | www  | skybird-lab.github.io. |

## Editing

Copy is in the HTML body; colours and type are CSS variables in `:root`.
