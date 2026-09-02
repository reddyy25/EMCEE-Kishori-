# Emcee Kishori — Portfolio Website

A premium, single-page portfolio website for Emcee Kishori, a multilingual
event host (English, Hindi, Telugu) based in Hyderabad — built from the
content and photos in her profile PDF.

## Run it

No build step required.

1. Extract this ZIP.
2. Open the folder in VS Code.
3. Right-click `index.html` → **Open with Live Server**
   (or just double-click `index.html` to open it in your browser).

## Structure

```
index.html          Main page (all sections)
css/style.css        Design system + layout + animations
js/script.js         Preloader, nav, scroll reveals, counters, lightbox
assets/images/       Photos & logo extracted from the source PDF
favicon/favicon.svg  Monogram favicon
```

## Notes

- Fonts (Anton + Manrope) load from Google Fonts via CDN — an internet
  connection is needed the first time a browser loads the page.
- All copy, stats, brand logos and photos are taken directly from the
  supplied PDF — nothing was invented.
- Colours, spacing and breakpoints are defined as CSS custom properties
  at the top of `style.css` if you want to retheme it.

## Mobile responsiveness update
This version includes an additional phone hardening pass for 320px–600px screens: full viewport width protection, no horizontal clipping, stacked hero layout, touch-friendly buttons, mobile navigation, and optimized gallery/stats/contact spacing.
