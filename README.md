# Mermaid Render

A lightweight, browser-only Mermaid editor that previews diagrams instantly and exports them as PNG files.

## GitHub Pages

This repository is a static site with no build step.

1. Open **Settings → Pages** in GitHub.
2. Select **Deploy from a branch**.
3. Choose `main` and `/(root)`.

The app is served directly from `index.html`. Mermaid is loaded from a pinned jsDelivr CDN URL, and diagram source stays in the browser's local storage.
