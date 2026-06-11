# kanae.ai static site

This directory is the first public entry point for `kanae.ai`.

It is intentionally a dependency-free static site:

- `index.html`
- `docs/index.html`
- `assets/kanae-hero.png` generated source
- `assets/kanae-hero-panels.png` cropped site hero asset

Preview locally by opening `index.html` in a browser, or serve the directory
with any static host. Suggested DNS split:

- `kanae.ai`: this top-level product entry
- `docs.kanae.ai`: customer docs and command references
- `download.kanae.ai`: gated signed release bundles and checksums
- `license.kanae.ai`: future license verification / issuance endpoint
