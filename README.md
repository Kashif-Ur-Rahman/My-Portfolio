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
- [mail/contact.php](mail/contact.php) — Server-side contact handler
- [LICENSE.txt](LICENSE.txt) — Template license

## Customization

- Change content and sections in `index.html`.
- Update styles in `scss/style.scss`, then compile to `css/style.css`.
- Edit scripts in `js/main.js` or replace/adjust libraries in `lib/`.
- Replace images inside `img/` and update paths in HTML where needed.

## Building & Deployment

You don't need a build step to run the site, but if you modify SCSS or want to bundle assets:

- Compile SCSS: `sass --watch scss:css`
- Minify JS/CSS with your preferred toolchain (optional)
- Deploy by pushing to GitHub and enabling GitHub Pages (set branch `main`, folder `/`), or host on Netlify/Vercel by connecting the repo.

## Credits & License

- Template: FreeFolio - Freelancer Portfolio Template by HTML Codex — https://htmlcodex.com/freelancer-portfolio-template
- Template license: https://htmlcodex.com/license (see [LICENSE.txt](LICENSE.txt))

If you redistribute or publish this site, please keep the original credit where appropriate according to the template license.

## Contributing

Contributions are welcome. Typical contributions:

- Fixing typos and improving copy
- Updating images or adding project case studies
- Improving accessibility or responsiveness

Suggested workflow:

1. Fork the repo.
2. Create a branch: `git checkout -b feature/your-change`.
3. Make changes and commit.
4. Open a pull request describing your changes.

## Contact

Update the contact form destination in `mail/contact.php` with your email. You can also add links to your email and social profiles in `index.html`.

---

If you'd like, I can also:

- Optimize the README for GitHub (badges, screenshots, live demo link).
- Add a small contributors guide or issue templates.

Tell me which you'd like next.

This is my Personal Portfolio repo.

## Live Demo

- Vercel: https://your-vercel-url.example (replace with your real URL)

## Screenshot

Add a screenshot at `docs/screenshot.png` and it will appear here:

![Screenshot](docs/screenshot.png)
