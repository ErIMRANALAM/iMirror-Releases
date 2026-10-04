# iMirror Website

Static product pages for `iMirror` by Our Apps World, published with GitHub Pages from the `ErIMRANALAM/iMirror-Releases` repository.

## Pages

- `index.html` — product landing page and illustrative interface preview.
- `manual/index.html` — web version of the USB/Wi-Fi user guide (`/manual/`).
- `privacy/index.html` — app-specific privacy policy draft (`/privacy/`).
- `styles.css` — responsive visual system shared by all pages.
- `assets/` — locally hosted SVG artwork, favicon, and 1200 × 630 social preview image.
- `sitemap.xml`, `robots.txt`, `llms.txt`, and `_redirects` — search discovery, AI-readable facts, and clean-URL redirects.

## Preview locally

From the repository root, run:

```sh
python3 -m http.server 8000 --directory website
```

Then open `http://localhost:8000/`, `http://localhost:8000/manual/`, or `http://localhost:8000/privacy/`.

The landing page links directly to the latest signed and notarized GitHub release. The product preview remains an illustration, not a live device screenshot. Review the privacy text against the final app build before each release.

The structured data, canonical links, Open Graph metadata, robots file, and sitemap target `https://erimranalam.github.io/iMirror-Releases/`.
