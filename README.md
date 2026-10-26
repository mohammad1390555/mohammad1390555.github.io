# Mohammad — Personal Portfolio

A lightweight, bilingual Persian/English portfolio for GitHub Pages.

**Live site:** https://mohammad1390555.github.io/  
**Public repositories:** curated bilingual descriptions, with public GitHub metadata refreshed automatically when available.  
**Languages:** Persian and English, with a saved language preference.

## Features

- Responsive blue design with featured projects and a compact mobile layout.
- Search, programming-language and category filters; sort by recommended order, stars, or name.
- Project cards include repository links, checked live demos, category labels, and GitHub star counts.
- Public repository names, languages, and star counts sync from GitHub's anonymous public API, cached in the visitor's browser for one hour; no personal access token is used or exposed.
- New public repositories can appear automatically with their public GitHub description; curated entries retain their bilingual copy.
- Open Graph/Twitter share image, canonical metadata, sitemap, robots policy, and Person structured data.
- Contact links for Telegram, Instagram and X.
- Keyboard skip link, visible focus states, reduced-motion support and a back-to-top control.
- Client-side measures that discourage ordinary text copying while keeping search/filter controls usable.
- No external fonts or runtime libraries; static project data is the fallback if GitHub is unavailable.

## Publishing

The site is a static HTML page. Keep `index.html`, `og-card.png`, `robots.txt`, and `sitemap.xml` at the repository root. Commit changes to the `main` branch to publish through the existing GitHub Pages setup.
