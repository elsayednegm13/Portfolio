# Personal Portfolio Website

A responsive single-page personal portfolio website built with HTML, CSS, and Bootstrap 5.

## Overview

This project is a personal portfolio website designed and developed using HTML, CSS, and Bootstrap. It presents personal information, case studies, testimonials, recent work, and contact details in a clean, modern, and fully responsive layout.

The site is currently a customizable template: the copy placeholders ("Your Name Here", "Work name here", intro text) are meant to be replaced with real content.

## Features

- Fully responsive design across all devices
- Built with HTML, CSS, and Bootstrap 5, with all assets served locally (no CDN dependency)
- Sticky navigation with smooth section scrolling
- Modern dark hero section with social links (LinkedIn, Behance, Twitter)
- Sections for Home, Case Studies, Testimonials, Recent Work, and Get In Touch
- Local icon sets: Bootstrap Icons and Font Awesome
- No build step and no framework: easy to customize and expand

## Tech Stack

- HTML5
- CSS3 (`normalize.css`, custom `style.css`)
- Bootstrap 5 (bundled in `css/bootstrap.css` and `js/bootstrap.bundle.js`)
- Bootstrap Icons and Font Awesome (bundled in `webfonts/`)

## Project Structure

```text
├── index.html        # Single-page portfolio markup
├── css/              # Bootstrap, icons, normalize, and custom styles
├── js/               # Bootstrap bundle and custom scripts
├── img/              # Images and favicon
└── webfonts/         # Icon fonts
```

## Running Locally

No installation or build step is required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder with any static server, for example:

```bash
npx serve .
```

## Deployment

The site is fully static, so it can be deployed as-is to any static host (GitHub Pages, Netlify, Cloudflare Pages, or shared hosting). Upload the repository contents and point the host at `index.html`.

## Customization

1. Replace the placeholder name, intro text, and section copy in `index.html`.
2. Swap the images in `img/` and the favicon.
3. Adjust colors and spacing in `css/style.css`.
