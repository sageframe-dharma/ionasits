# Iona Sits

Single-page site for Iona's babysitting and mother's-helper work in Cambridge, MA.

## Structure

- `index.html` — the entire site; styles are inline, no build step
- `img/` — photography

Fonts load from Google Fonts. The contact form posts to Formspree.

## Deployment

Cloudflare Pages, project `ionasits`, served at https://ionasits.pages.dev.
Connected to this repo — every push to `main` deploys. No build command;
the repository root is the output directory.

## Development

Open `index.html` in a browser. There is nothing to build.
