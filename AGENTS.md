# AGENTS.md

## Cursor Cloud specific instructions

This repo is a single static website (no build step, no package manager, no tests, no lint tooling). Source lives in `sat-portfolio/` (`index.html`, `styles.css`, `script.js`, `assets/`). The `CNAME` file configures the custom domain for GitHub Pages.

### Running it

Serve the `sat-portfolio/` directory over HTTP (opening `index.html` via `file://` works too, but a server matches production behavior):

```bash
cd sat-portfolio && python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

### Notes / gotchas

- There are no dependencies to install, so the startup update script is effectively a no-op.
- There is no build/lint/test pipeline. "Testing" means loading the page in a browser and exercising the JS (nav smooth-scroll, scroll animations, contact form).
- The contact form (`#contactForm`) has no backend — on submit it builds a `mailto:` link and triggers the OS mail handler, then shows a green in-page success notification. In a headless/VM browser the OS "choose mail application" dialog may appear; this is expected and can be dismissed.
- The site is published via GitHub Pages from this repo (`CNAME` -> `satteches.com`).
