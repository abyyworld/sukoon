# Sukoon

Sukoon maps Islamic finance in Uzbekistan: your goal in, real options out, with sources and verification dates.

## Hosting

The whole site is a single static file, `index.html`. There is no build step and nothing to install.

- Upload `index.html` to the web root of any static host (Nginx, Apache, GitHub Pages, Netlify, Vercel, Cloudflare Pages, etc.).
- Routing uses URL hashes (`#/product/...`, `#/compare`), so no server rewrite rules are needed.
- Fonts load from Google Fonts; everything else is inline.
- To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.

Note: the "Ask AI" explanations only work inside claude.ai. On any other domain that panel shows the rule text from the built-in data instead, and the free-text goal box falls back to built-in keyword parsing. Everything else works as normal.
