# Samuel C. Rhodes Academic Website

This repository contains the review-only static preview of Samuel C. Rhodes’s academic website.

## Preview

The temporary review build is published at <https://samuel-rhodes.github.io/>.

The custom domain is **not connected** during this review pass. The build is intentionally marked `noindex` until a later, separately authorized production launch.

## Structure

- `index.html` — single-page academic website
- `404.html` — custom not-found page
- `assets/css/styles.css` — local responsive styles
- `assets/images/` — documented local imagery
- `assets/icons/favicon.svg` — local SR monogram
- `ATTRIBUTIONS.md` — public image source and rights notes
- `robots.txt` — permits crawlers to read the page-level `noindex` directive
- `.nojekyll` — serves the static files directly on GitHub Pages

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.

## Launch checklist placeholder

The production launch is outside this pass. A later authorized launch should:

- remove the page-level `noindex` directives;
- add the production canonical URL and sitemap;
- connect the approved custom domain only after DNS and redirect planning;
- revalidate links, accessibility, responsive layouts, and search metadata.

No analytics, trackers, forms, external fonts, JavaScript libraries, frameworks, build dependencies, or GitHub Actions workflows are used.

## Pass 2 review state

The Pass 2 preview retains the Washington hero and adds two locally stored, documented web derivatives: Samuel C. Rhodes’s authorized 2024 headshot in About and the exact Ronald Reagan classroom photograph from the prior academic site in Teaching. Source images and validation records remain outside the public repository.
