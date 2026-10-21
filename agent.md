# SEO for www.maerki.com

## Goal

Prepare this static website so search engines can index it after deployment. For now, make and verify changes against the local files; do not deploy the site.

## Site structure

- `www_maerki_com/` is the site root and will be published at `https://www.maerki.com/`.
- The album pages are under `www_maerki_com/hans/album/` and will be published under `https://www.maerki.com/hans/album/`.

## Work

1. Review the existing pages and determine which SEO files and metadata are appropriate.
2. Add or update the root-level `robots.txt` and sitemap files as needed.
3. Include the album pages in the sitemap.
4. Verify that generated URLs correspond to the intended public URLs, not local filesystem paths.

Use a sitemap index only if the site needs multiple sitemap files. A separate `robots.txt` for the album subdirectory is not normally used; configure crawling rules in the site-root `robots.txt`.
