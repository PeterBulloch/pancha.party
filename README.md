# Pancha Party

A small parody site celebrating Pancha, with Korean and English text, a store showcase, and a clicker game.

## Run locally

Open `public/index.html` in a browser. The site is static and requires no build or dependencies.

## Structure

- `public/index.html` contains the page and game logic.
- `public/styles.css` contains the styles.
- `public/translations.js` contains the Korean and English translations.
- `public/images/` contains the site images.

Pushes to `main` deploy the contents of `public/` via the workflow in `.github/workflows/deploy.yml`.