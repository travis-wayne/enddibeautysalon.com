# Enddi Beauty Salon and Makeup

This is the codebase for the website of Enddi Beauty Salon and Makeup, inspired by The Damai Bali. The site is a static HTML/CSS/JS project designed for a luxury beauty and wellness experience.

## Project Structure

- **index.htm**: Main landing page.
- **dining.html, relax.html, stay.html, discover.html**: Section pages for different experiences and services.
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

## How to Use

1. Open any `.html` file in a browser to view the site.
2. All assets are local; no build step is required.
3. For development, edit the HTML, CSS, or JS files directly.
4. To further optimize, you can re-minify CSS or run PurgeCSS as needed.

## Customization
- Update images in `assets/img/` and `media/images/` as needed.
- Add or update fonts in `assets/fonts/` and reference them in CSS.
- Edit content in HTML files for your own branding or services.

## Credits
- Design and code by Dennis (original CSS comments).
- Inspired by The Damai Bali and Enddi Beauty Salon and Makeup.

---

For any questions or further customization, please contact the site maintainer.

