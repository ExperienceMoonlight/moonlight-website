# Moonlight website

Minimal static website foundation for the Moonlight project.

## Structure

- `index.html` — empty page shell with metadata and relative asset links.
- `assets/css/styles.css` — reserved for future styles.
- `assets/js/main.js` — reserved for future behavior.
- `assets/images/` — reserved for supplied images.
- `.nojekyll` — serves the files as a plain static site on GitHub Pages.

No build step or dependencies are required. Open `index.html` in a browser to preview it; the page is intentionally blank until content and design are supplied.

## Future GitHub Pages deployment

When ready to publish, open the repository's **Settings → Pages**, select **Deploy from a branch**, and choose **main** and **/ (root)**. Save the settings.

Keep asset paths relative (for example, `assets/images/poster.jpg`) so they work under the repository's GitHub Pages path.

Branding, logos, marketing copy, event information, and visual design will be supplied separately.
