# Riwaayat — Saree Boutique Demo

A responsive, animated saree storefront demo built with React, Vite, Framer Motion and React Three Fiber.

## Features
- Premium editorial storefront design with responsive mobile navigation
- Animated hero section with crossfading slides and a live Three.js / React Three Fiber 3D ornament
- Product collection grid with animated filter/sort changes, category, colour and price filters, sorting, and search suggestions
- Responsive product gallery, quick-view modal, saved-sarees wishlist drawer and working cart drawer with quantity controls
- Interactive cloth-like 3D silk presentation with a reduced-motion mode and lightweight mobile fallback
- Editorial saree gallery, bridal and handloom edits, artisan storytelling and customer-note sections
- Staggered scroll reveals, refined hover/CTA transitions, animated search and product overlays, reduced-motion support, responsive WebP photography, and interactive 3D ornament and silk presentation
- Demo checkout interaction, newsletter signup feedback and toast notifications
- Craft, brand story, journal, newsletter and footer sections
- Sample product data and saree-focused Pexels photography served in responsive WebP sizes

## Run locally

Requirements: Node.js 20.19+ or 22.12+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Production build

```bash
npm run build
npm run preview
```

The production files are generated in `dist/`.

## Customize
- Product data and categories: `src/main.jsx` (`products`, `categories`)
- Store name, content and sections: `src/main.jsx`
- Theme, responsive styles and animations: `src/style.css`
- Page title and font imports: `index.html`

## Demo limitations
This is a frontend demonstration. Cart state is held in memory and resets on refresh. Checkout does not process payments or create orders. Connect a backend, inventory API, shipping provider and payment gateway before accepting real orders. Product photography is delivered from Pexels and requires an internet connection; replace sample items and editorial imagery with commissioned product photography before launch.
