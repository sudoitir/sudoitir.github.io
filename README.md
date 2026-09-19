# sudoitir.github.io

Personal site, served as-is by GitHub Pages (`.nojekyll`, no build step).

This repo owns the host root, so it holds the files crawlers only read there:

- `robots.txt` — lists the sitemap of every project site; add a `Sitemap:` line when a new project gets Pages.
- `sitemap.xml` — the root page only; each project site publishes its own.
- `google*.html`, `BingSiteAuth.xml` — Search Console / Bing Webmaster verification for the `https://sudoitir.github.io/` property, which covers every project site under it.
