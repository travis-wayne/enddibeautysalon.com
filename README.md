
# Enddi Beauty Salon and Makeup

This is the codebase for the website of Enddi Beauty Salon and Makeup, inspired by The Damai Bali. The site is a static HTML/CSS/JS project designed for a luxury beauty and wellness experience.

## Recent Updates (June 2025)

- **New Page:** `nails.html` — A dedicated, fully styled page for nail services, featuring formal and friendly content to attract customers. All text is focused on nail care, artistry, and premium service.
- **Content Rewrite:** All text in `nails.html` was rewritten to be formal, friendly, and focused on nails, with customer-attracting language.
- **Performance Optimizations:**
  - All major HTML pages now use `<picture>` with WebP and fallback images for next-gen image support.
  - All `<img>` tags use `loading="lazy"` for lazy loading.
  - CSS is minified (`style.min.css`) and purged of unused styles using PurgeCSS.
  - Main CSS is loaded asynchronously with `<link rel="preload" ... onload="this.rel='stylesheet'">` and `<noscript>` fallback.
  - Key assets (fonts, hero images) are preloaded for faster user experience.
- **SEO & Social:** Updated meta tags for SEO, Open Graph, and Twitter Cards, especially for the new nails page.
- **README:** This documentation was updated to reflect all new features and optimizations.


## Project Structure

- **index.htm**: Main landing page.
- **dining.html, relax.html, stay.html, discover.html, nails.html**: Section pages for different experiences and services.
- **assets/**: Contains all static assets.
  - **css/**: Stylesheets (including minified and purged CSS for performance).
  - **fonts/**: Custom and web fonts (WOFF2, OTF, TTF).
  - **icons/**: SVG icons.
  - **img/**: Images and graphics (WebP, JPG, PNG, SVG).
  - **js/**: JavaScript files and GSAP plugins.
- **media/**: Additional images and videos for the site.
- **packages/**: Special offer and package HTML pages.
- **stay/**, **discover/**: Subpages for specific experiences.


## Features & Optimizations

- **Next-Gen Images**: Uses WebP for faster loading, with fallbacks for older browsers.
- **Lazy Loading**: All images use `loading="lazy"` for performance.
- **Minified & Purged CSS**: CSS is minified and unused styles are removed using PurgeCSS.
- **Async CSS Loading**: Main CSS is loaded asynchronously for faster first paint.
- **Preload Key Assets**: Fonts and hero images are preloaded for better user experience.
- **SEO & Social**: Includes meta tags for SEO, Open Graph, and Twitter Cards.
- **Dedicated Nails Page**: `nails.html` offers a formal, customer-focused presentation of all nail services.


## How to Use

1. Open any `.html` file in a browser to view the site.
2. All assets are local; no build step is required.
3. For development, edit the HTML, CSS, or JS files directly.
4. To further optimize, you can re-minify CSS or run PurgeCSS as needed.


## Customization
- Update images in `assets/img/` and `media/images/` as needed.
- Add or update fonts in `assets/fonts/` and reference them in CSS.
- Edit content in HTML files for your own branding or services.
- To add new service pages, duplicate an existing section page and update the content and structure as needed.

## Credits
- Design and code by Dennis (original CSS comments).
- Inspired by The Damai Bali and Enddi Beauty Salon and Makeup.

---

For any questions or further customization, please contact the site maintainer.

