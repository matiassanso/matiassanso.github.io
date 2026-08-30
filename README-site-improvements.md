# Site improvements: styles extraction, accessibility, SEO

This branch (site-improvements) contains the following changes:

- Extracted inline CSS to `assets/css/styles.css` and added a minified `assets/css/styles.min.css`.
- Replaced the original `index.html` with an improved, accessible version that:
  - Fixes charset and unclosed tags
  - Adds skip-link, main element, ARIA labels
  - Adds SEO meta tags and structured data (JSON-LD)
  - Adds a small accessible mobile nav toggle script
  - Uses a responsive image with srcset and lazy loading
- Added placeholder images and a favicon (`assets/images/foto-placeholder.svg`, `assets/favicon.svg`). Replace with optimized WebP/PNG files named `foto-profesional.webp` and `foto-profesional@2x.webp`.

Next steps for you:
1. Replace the placeholder image(s):
   - Upload optimized images to `assets/images/` named exactly:
     - `foto-profesional.webp` (1x)
     - `foto-profesional@2x.webp` (2x)
   - If you prefer PNG/JPEG, update `index.html` accordingly.

2. (Optional) Extract Google Fonts and host locally, or limit font weights to improve performance.
3. Test the site locally or via GitHub Pages and open a PR review to merge to main.

I can also:
- Generate actual WebP images if you upload the original photo here or give a URL to fetch it from.
- Create a pull request from this branch into main (I will create one when you ask).
