# YŪGEN Restaurant Website

A sleek, modern restaurant website for YŪGEN, a contemporary Japanese dining experience. The project is built as a static marketing site with multiple pages for the home, story, menu, reservations, and contact experience.

## Overview

This site presents a premium Japanese restaurant brand with:

- a refined hero section and brand-focused landing page
- informational pages for About and Menu
- reservation and contact entry points
- responsive navigation for mobile and desktop layouts
- elegant styling with a warm, luxury-inspired palette

## Tech Stack

- HTML5
- CSS3
- Tailwind CSS v4
- Vanilla JavaScript

## Project Structure

```bash
.
├── public/
│   ├── about.html
│   ├── booking.html
│   ├── contact.html
│   ├── index.html
│   ├── menu.html
│   ├── style.css
│   └── images/
├── src/
│   └── style.css
├── package.json
├── package-lock.json
└── README.md
```

## Features

- Fully static multi-page layout
- Japanese-inspired premium visual design
- Mobile-friendly navigation toggle
- Menu sections for sushi, signature rolls, sashimi, and drinks
- Booking-focused CTA buttons and brand storytelling

## Local Setup

1. Install dependencies:

```bash
npm install
```

2. Build the generated CSS:

```bash
npm run build
```

3. Preview the app locally:

```bash
cd public
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

You can also open `public/index.html` directly in a browser if you only want a quick preview.

## Scripts

The project includes the following npm script:

```bash
npm run build
```

This compiles the Tailwind source from `src/style.css` into the generated stylesheet used by the site in `public/style.css`.

## Customization

You can update the restaurant branding, colors, layout, and content by editing:

- `public/*.html` for page content and structure
- `src/style.css` for Tailwind theme values and custom styles
- `public/images/` for restaurant photography and assets

## Notes

This application is intentionally lightweight and does not depend on a framework or backend. It is suitable for a static portfolio or restaurant marketing website that can later be extended with a real booking system or CMS.
