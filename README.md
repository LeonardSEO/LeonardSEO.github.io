# Leonard van Hemert — GitHub Pages portfolio

This repository publishes the personal portfolio of Leonard van Hemert at [leonardseo.github.io](https://leonardseo.github.io/).

The site is deliberately static and dependency-free. It includes responsive light and dark themes, semantic HTML, accessible navigation, canonical and social metadata, `ProfilePage`/`Person` structured data, `robots.txt`, an XML sitemap, and an `llms.txt` summary.

## Google Search Console verification

Use a **URL-prefix property** for `https://leonardseo.github.io/`.

1. Open Google Search Console and add `https://leonardseo.github.io/` exactly, including `https://` and the trailing slash.
2. Choose **HTML file upload** under the available verification methods.
3. Download the unique verification file supplied by Google. Its name normally starts with `google` and ends in `.html`.
4. Add that exact file, without renaming or changing its contents, to the root of this repository next to `index.html`.
5. Publish the change and confirm that `https://leonardseo.github.io/<google-verification-file>.html` returns the exact file with HTTP 200 in an incognito window.
6. Select **Verify** in Search Console.
7. Submit `https://leonardseo.github.io/sitemap.xml` in the Sitemaps report.
8. Inspect `https://leonardseo.github.io/` and request indexing.

Keep the verification file in the repository after verification; Search Console checks it periodically. If Search Console only offers DNS verification, cancel that property and create a **URL-prefix property** instead of a Domain property. The `github.io` DNS zone is owned by GitHub and cannot be verified through this account.

## Local preview

Serve the repository root with any static HTTP server and open the local URL in a browser. Absolute production metadata deliberately points to the canonical GitHub Pages URL.
