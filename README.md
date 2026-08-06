# AAL Xolutions G2 landing

Live at **https://g2.aalxolutions.com/**

Static single-page site served by GitHub Pages. Client: AAL Xolutions
(Carlos Escudero). Built and maintained by IBS.

- `index.html` — the whole page (inline CSS + JS, Three.js from CDN)
- `assets/` — logo, hero video/poster, and the six G2 cube face images
- `CNAME` — custom domain for GitHub Pages

DNS lives on the client's Squarespace account: `g2` CNAME to `ooak21.github.io`.
Apex, `my`, and `links` belong to GoHighLevel and are not managed here.

Lead capture posts to the Supabase `aal-lead-intake` edge function.
