# Venus Accesorios

A simple static website that showcases the **Venus Accessories** collection — a catalog of exclusive jewelry and accessories available for immediate delivery.

## Overview

The site presents a product catalog organized by category, letting visitors browse new and available accessories. Every item includes a photo, a short description, and its price (in Colombian pesos). Contact channels (WhatsApp and Instagram) are included so customers can place orders directly.

## Categories

- **Cadenas** (Necklaces) — stainless steel and rhodium-plated necklaces, pendants, and jewelry sets.
- **Anillos** (Rings) — rings in cover gold with micro zirconia, plus stainless steel options.
- **Aretes, pulseras y tobilleras** (Earrings, bracelets, and anklets) — stainless steel pieces.

## Pages

| File | Description |
| --- | --- |
| `index.html` | Home page with links to each catalog category. |
| `html/cadenas.html` | Necklaces catalog. |
| `html/anillos.htm` | Rings catalog. |
| `html/aretes.html` | Earrings, bracelets, and anklets catalog. |

## Tech Stack

- **HTML5** for structure.
- **CSS** — custom stylesheets with a gold-and-brown theme, Playfair Display / Great Vibes fonts, and responsive mobile media queries.
- **Bootstrap 5.3** (CDN) for layout utilities.
- **Font Awesome 6** (CDN) for the social icons.

## Structure

```
venus/
├── index.html
├── css/
│   ├── style.css        # Home page styles
│   └── catalogo.css     # Catalog page styles
├── html/
│   ├── cadenas.html     # Necklaces catalog
│   ├── anillos.htm      # Rings catalog
│   └── aretes.html      # Earrings, bracelets & anklets catalog
└── imagenes/            # Product photos grouped by category
    ├── anillos/
    ├── aretes/
    ├── cadenas/
    ├── pulseras/
    └── tovilleras/
```

## Getting Started

The site is fully static and needs no build step or dependencies. Just open the project in **Visual Studio Code** and use the **Live Server** extension (right-click on `index.html` → "Open with Live Server").

## Notes

- Product prices are listed in Colombian pesos (COP).
- The WhatsApp and Instagram links are placeholders; update the `href` values with the real contact URLs before publishing.
- Some descriptions and product names contain minor typos inherited from the source catalog.

## License

© 2025 Venus Accesorios — All rights reserved.
