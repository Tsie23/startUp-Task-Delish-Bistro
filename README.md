# Delish Bistro — Static Site

Small static landing page for a restaurant. Open the site in a browser to preview.

## Files in this workspace
- [index.html](index.html)
- [style.css](style.css)

## Project overview
A responsive single-page static site with:
- Hero header with background image
- Navigation bar
- Menu grid
- About section
- Contact form
- Footer

## How to view locally
1. Open [index.html](index.html) in your browser (double-click or right-click → Open with...).
2. For live reload while editing, use the VS Code *Live Server* extension and serve the folder.

## Notes & quick fixes
- The hero background uses `hero.jpg` (not included). Add an image at the project root or update `background-image` in [style.css](style.css).
- In [index.html](index.html):
  - Menu nav link currently uses `href="menu"` — change to `href="#menu"` to scroll to the menu section.
  - Typo: label "Surame" should be "Surname".
- Contact form posts to `/contact`. For static hosting, replace action or handle via a form service.

## Accessibility & responsiveness
- Uses semantic sections and labels.
- Navigation and layout are responsive via media queries in [style.css](style.css).
- Ensure sufficient color contrast for text over images (consider increasing overlay opacity in `.hero-content`).

## License
Add a license file if you plan to publish (e.g., MIT). This repository currently contains only static demo assets.