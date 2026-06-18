---
name: seo-sitemap-pro
description: Use for /seo, /sitemap, SEO testing, sitemap.xml, robots.txt, metadata, canonical URLs, Open Graph, structured data and indexing.
---

# SEO Sitemap Pro

Audit and improve search readiness.

## Inspect

- Routing and page structure.
- Metadata generation.
- Canonical URLs.
- Sitemap generation.
- robots.txt.
- Open Graph and Twitter card tags.
- Structured data where appropriate.
- Internal links and crawl paths.
- Status codes, redirects and duplicate routes.

## Rules

1. Do not expose private/admin/student data in sitemaps.
2. Do not index staging, auth-only, payment, dashboard or private pages.
3. Canonical URLs must be stable and absolute.
4. Sitemap URLs should be valid, normalized, HTTPS in production and not blocked by robots.txt.
5. Add tests or scripts for sitemap, robots and metadata when possible.

## Deliverables

Prefer scripts or tests that verify sitemap URL validity, robots behavior, metadata helpers and intentional noindex decisions.
