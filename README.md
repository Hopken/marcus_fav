# marcus_fav — Marcus Khoko Portfolio

This repository contains a small, responsive portfolio site for Marcus Khoko. It showcases a hero section, about, projects, skills and contact sections. The project is static and intended to be served from any static hosting (GitHub Pages, Netlify, Vercel, etc.).

## What’s included

- `index.html` — main site with semantic sections and SEO metadata (Open Graph, Twitter Card, JSON-LD)
- `assets/css/style.css` — modern responsive styles
- `assets/images/` — image assets used for logo and thumbnails (replace with your own)
- `sitemap.xml` — simple sitemap (update domain)
- `robots.txt` — crawler instructions pointing to the sitemap

## Quick preview (local)

From the project root (where `index.html` lives) run a simple static server and open http://localhost:8000

```bash
# start a simple HTTP server (Python 3)
python3 -m http.server 8000
```

## SEO & deployment notes

- Replace all `https://your-domain.example/` placeholders in `index.html`, `sitemap.xml` and `robots.txt` with your real site URL before deploying.
- Replace social handles in the JSON-LD (`sameAs`) and Twitter meta tag (`@your_twitter`).
- After deploying, submit the `sitemap.xml` URL to Google Search Console and Bing Webmaster Tools.

## Next steps & suggestions

- Replace placeholder project cards with real projects and unique per-page metadata where applicable.
- Add accessible focus styles and keyboard navigation improvements.
- Add real share buttons or meta tags per-project for improved social previews.

## License & credits

You can reuse and modify this code. Add a license file if you want to specify permissions.

---
