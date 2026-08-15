# Samuel C. Rhodes Academic Website

This repository contains the production static website for Samuel C. Rhodes.

## Production

The canonical site is <https://www.samrhodesphd.com/>.

GitHub Pages publishes from `main` at the repository root. The custom domain is `www.samrhodesphd.com`, HTTPS enforcement is active, the homepage is indexable, and the custom `404.html` remains `noindex`.

The production sitemap is <https://www.samrhodesphd.com/sitemap.xml>. This repository does not claim that a search engine has already indexed the site.

## Structure

- `index.html` — single-page academic website and production metadata
- `404.html` — custom not-found page; intentionally `noindex`
- `CNAME` — GitHub Pages custom domain; preserve exactly as `www.samrhodesphd.com`
- `sitemap.xml` — canonical homepage only
- `robots.txt` — permits crawling and declares the production sitemap
- `assets/css/styles.css` — local responsive styles
- `assets/images/` — documented local imagery
- `assets/icons/favicon.svg` — local SR monogram
- `ATTRIBUTIONS.md` — public image source and rights notes
- `.nojekyll` — serves the static files directly on GitHub Pages

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.

## Maintenance

Preserve `CNAME`, keep the custom 404 `noindex`, and update the sitemap `lastmod` only when homepage content or metadata is deployed. Before publishing, validate the canonical URL, robots directives, sitemap, JSON-LD, social metadata, local assets, external links, redirects, responsive layouts, and HTTPS behavior.

The curriculum vitae remains externally hosted on Dropbox at <https://www.dropbox.com/scl/fi/5q4mvbvx5kduhftkxqccl/samuel_rhodes_CV.pdf?rlkey=bo6b60njrqkesnyrqj9zi7zkp&raw=1>. Do not copy it into this repository.

No analytics, trackers, forms, external fonts, JavaScript libraries, frameworks, build dependencies, CMS, or GitHub Actions workflows are used.
