# Leonard van Hemert — GitHub Pages portfolio

This repository publishes the personal portfolio of Leonard van Hemert at [leonardseo.github.io](https://leonardseo.github.io/).

The site is deliberately static and dependency-free. It includes responsive light and dark themes, semantic HTML, accessible navigation, canonical and social metadata, `ProfilePage`/`Person` structured data, `robots.txt`, an XML sitemap, and an `llms.txt` summary.

## Google Search Console verification

Use a **URL-prefix property** for `https://leonardseo.github.io/`.

1. Open Google Search Console and add `https://leonardseo.github.io/` exactly, including `https://` and the trailing slash.
2. Choose the **HTML tag** verification method.
3. Copy the complete verification tag supplied by Google.
4. Add it in `index.html` directly under the `Google Search Console` comment in the `<head>`.
5. Publish the change and confirm that the tag appears in the live HTML source.
6. Select **Verify** in Search Console.
7. Submit `https://leonardseo.github.io/sitemap.xml` in the Sitemaps report.
8. Inspect `https://leonardseo.github.io/` and request indexing.

Keep the verification meta tag in `index.html`; Search Console checks it periodically.

## Local preview

Serve the repository root with any static HTTP server and open the local URL in a browser. Absolute production metadata deliberately points to the canonical GitHub Pages URL.
