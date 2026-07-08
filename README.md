# My-Portfolio

[![Demo](https://img.shields.io/badge/demo-online-brightgreen)](https://vercel.app/) [![Deploy](https://img.shields.io/badge/deploy-vercel-black?logo=vercel)](https://vercel.app/)

Freelancer portfolio website and repository for personal use.

## Overview

This repository contains a responsive, single-page freelancer portfolio. It includes HTML, CSS/SCSS, JavaScript, and supporting libraries to showcase projects, provide contact functionality, and display galleries and carousels.

## Demo

- Open the site locally: [index.html](index.html)

## Quick Start

1. Clone the repository or download the ZIP.
2. To preview locally, you can open `index.html` directly in your browser or run a simple server:

```bash
# Python 3 built-in server (from repo root)
python -m http.server 8000

# then visit http://localhost:8000
```

3. If you edit SCSS, compile it to CSS (one option):

```bash
# Install Dart Sass if needed, then:
sass --watch scss:css
```

## Repository README vs Project README

This `README.md` serves both as the project README (how to run and customize the portfolio) and the repository README (what the repo contains and how to contribute). Use the sections below as a guide to develop, customize, and deploy the site.

## Features

- Responsive layout and mobile-first design
- Project/gallery lightbox and isotope filtering
- Owl Carousel and typed text effects
- Contact form (server-side script in `mail/contact.php`)
- SCSS source files for easy customization

## File Structure (important files)

- [index.html](index.html) — Main HTML file
- [css/style.css](css/style.css) — Compiled styles
- [scss/style.scss](scss/style.scss) — Source SCSS
- [js/main.js](js/main.js) — Main JavaScript
- [img/](img/) — Images and assets
- [lib/](lib/) — Third-party libraries (owlcarousel, lightbox, isotope, etc.)




## Contributing

Contributions are welcome. Typical contributions:

- Fixing typos and improving copy
- Updating images or adding project case studies
- Improving accessibility or responsiveness


## Live Demo

- Vercel: https://kashif-ur-rahman-portfolio.vercel.app/


