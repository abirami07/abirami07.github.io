# Abirami Kumar — Interactive Editorial Portfolio

A responsive, accessible, static portfolio for GitHub Pages. Built with HTML, CSS, and vanilla JavaScript; no build step required.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` in this directory and visit http://localhost:8000.

## Publish on GitHub Pages

1. Open your GitHub repository `abirami07/abirami07.github.io`.
2. Back up your existing site files (or create a new branch).
3. Upload the **contents** of this folder to the repository root: `index.html`, `styles.css`, `script.js`, and `assets/`.
4. Commit. Under Settings → Pages, use **Deploy from a branch**, `main`, `/ (root)` if not already configured.
5. Visit https://abirami07.github.io/ after deployment completes.

## Customize

- Edit introductory text and experience entries in `index.html`.
- Edit the project case-study descriptions and links in `script.js` (`projects` object).
- Edit palette and typography in `styles.css` (`:root`).
- Replace photos in `assets/` with your preferred originals while retaining filenames or updating `index.html`.
- The project visuals are CSS/SVG illustrations, not screenshots of your applications. Replace them with real product screenshots when available.

## Features

Scroll reveals (with reduced-motion support), scroll progress, responsive menu, project category filters, keyboard-accessible project dialogs, photo lightbox, and hover transitions. External font loading requires an internet connection; system font fallbacks are included.

## Before publishing

Confirm the exact AP0110 record count, project descriptions, and current experience dates. The portfolio uses 4,907 records from the more recent resume and omits Wnted.

Photo files are stored in `assets/`. Keep this folder alongside `index.html` when deploying to GitHub Pages.
