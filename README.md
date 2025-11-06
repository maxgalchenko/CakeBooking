# CakeBooking

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Gulp](https://img.shields.io/badge/Gulp-DB4446?style=for-the-badge&logo=gulp&logoColor=white)](https://gulpjs.com/)
[![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A?style=for-the-badge&logo=postcss&logoColor=white)](https://postcss.org/)
[![BrowserSync](https://img.shields.io/badge/BrowserSync-FF69B4?style=for-the-badge)](https://browsersync.io/)

</div>

## Overview

Static frontend demo for a booking listings UI with map pins, filters, and cards. Built as a learning project using a Gulp 4 pipeline to compile assets and serve the site with live reload.

## Key Features

- Interactive map pins rendering with modular JS
- Filter form and basic validation to refine listings
- Card UI for viewing ad details

## Tech Stack

HTML5, CSS3, Vanilla JS (ES6), Gulp 4, PostCSS (Autoprefixer, cssnano), BrowserSync, imagemin/webp

## Architecture

Static site compiled from `src/` to `docs/` using Gulp: copies JS modules, minifies CSS/HTML, optimizes images (including WebP generation), and serves via BrowserSync with live reload.

## Performance & Accessibility

Minified CSS/HTML, optimized assets with WebP, and basic caching via BrowserSync. Uses semantic HTML where possible; simple, keyboard-accessible form controls.

## Quality

- Linting: None • Formatting: Prettier
- Type safety: N/A
- Tests: None
- CI: None • Coverage: N/A

## Prerequisites

- Node.js: `18.17.0`

## Installation

```bash
git clone https://github.com/maxgalchenko/cakebooking.git
cd cakebooking
npm install
```

## Quick Start

```bash
npx gulp dev
# Production
npx gulp build
# Then open ./docs/index.html
```

Open http://localhost:3000

## Available Scripts

- `npm test` – placeholder script (exits with error; no tests configured)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
