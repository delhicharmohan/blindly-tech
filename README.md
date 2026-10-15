# Blindly Engineering

Tech updates from the team building [Blindly](https://blindly.date/), the voice-first blind dating app in India.

Live site: https://delhicharmohan.github.io/blindly-tech/

## Posting an update

Add a Markdown file to `_posts/` named `YYYY-MM-DD-short-title.md`:

```markdown
---
title: "Your post title"
description: "One or two sentences. Used for Google snippets and social cards."
tags: [release]
---

Post body in Markdown.
```

Commit and push to `main`. GitHub Pages rebuilds the site, and the sitemap (`/sitemap.xml`) and RSS feed (`/feed.xml`) update automatically.

## Search indexing

- SEO tags, Open Graph, canonical URLs and JSON-LD come from `jekyll-seo-tag`.
- `sitemap.xml` comes from `jekyll-sitemap`; `robots.txt` points to it.
- To verify in Google Search Console, add the site as a URL-prefix property, pick the HTML tag method, paste the token into `webmaster_verifications.google` in `_config.yml`, push, then submit `sitemap.xml`.
