# REBT - GitHub Pages source for Copilot Agent

This repository contains a single-page, crawler-friendly HTML version of the Spanish Reglamento Electrotécnico para Baja Tensión (REBT) and ITC-BT sections.

Use this URL in Copilot public website knowledge:

```text
https://jlgarciatucci.github.io/REBT/
```

Do not use GitHub blob URLs such as `https://github.com/.../blob/main/README.md`.

## Files

- `index.html`: Full structured HTML content with headings, reconstructed tables, and extracted PDF images.
- `images/`: Embedded images extracted from the source PDF, referenced by `index.html`.
- `robots.txt`: Allows crawling and points to sitemap.
- `sitemap.xml`: Public page URL for discovery.
- `.nojekyll`: Prevents Jekyll processing issues.

## Copilot agent guidance

Configure the agent to answer only from this REBT source, cite article/ITC/table references, reproduce source tables when relevant, and avoid using memory or external/confidential information.
