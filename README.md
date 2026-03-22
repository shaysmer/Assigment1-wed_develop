# Assignment1 - Web Development

This repository contains static HTML, CSS, and JavaScript files for a web development assignment.
It is structured as a small multi-page site, with each page having a matching stylesheet and script
file ready for styling and interactivity.

## Project structure

- Pages
  - `adopt.html`
  - `body.html`
  - `dog.html`
  - `thankyou.html`
- Page-specific assets
  - `adopt.css` / `adopt.js`
  - `body.css` / `body.js`
  - `dog.css` / `dog.js`
  - `thankyou.css` / `thankyou.js`
- Shared assets
  - `styles.css`
  - `script.js`

> Note: The HTML files currently include basic boilerplate and can be filled in as part of the
> assignment. Add `<link>` and `<script>` tags as needed to connect the CSS and JS files.

## Run locally

There is no build step. You can:

1. Open any HTML file directly in your browser, or
2. Serve the folder with a simple static server (recommended for relative paths):

   ```bash
   python3 -m http.server 8000
   ```

   Then visit `http://localhost:8000/adopt.html` (or another page).

## Tests

No automated tests are configured. Running `npm test` will report that no tests are specified.
