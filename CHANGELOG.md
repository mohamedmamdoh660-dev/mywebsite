# CHANGELOG

All notable changes to this project will be documented in this file.

## [2026-05-25] - Initial Release - Book Breakdown AR Website
- Created the core `book-breakdown-ar.html` single-page application with support for hash routing (`#home`, `#episodes`, `#books`, `#about`, `#start`).
- Implemented a custom-designed dark-mode-first aesthetic (copper accent `#c8843a`, dark background `#0c0b0a`) with warm off-white tones, Cairo headers, and Tajawal body font.
- Designed a custom light/dark mode toggle button with SVG icons, utilizing localStorage and inline meta/document configuration to prevent page flash (FOUC).
- Added an interactive filterable archive for episodes with instant category and search logic.
- Built a library of books with dynamic 3D-styled CSS/SVG covers, rotating and scaling on hover.
- Programmed a custom interactive "Start Here" quiz recommending personalized video streams step-by-step based on the user's specific problem.
- Implemented native CSS scroll reveal animations with high-fidelity JavaScript IntersectionObserver fallback.
- Saved user's official `logo.png` logo and embedded it into the header, footer, and about page with text fallback.
- Added project documentation in `docs/documentation.md`.
- Added `nixpacks.toml` configuration to copy static assets to a `dist/` directory during build, resolving Coolify's default static-site `dist/` folder requirement.
- Created static Terms of Service (`terms.html`) and Privacy Policy (`privacy.html`) pages, linked them in the footer of the main website, and updated build command in `nixpacks.toml` to copy all HTML files.
- Integrated an interactive HTML5 canvas glowing particle background in Javascript and CSS, inspired by the Stanford Fairer Tomorrow website design, adding motion depth and floating light particles reacting to mouse movements.
- Rebuilt design system featuring cinematic letterbox bars, bold typographic pairings of Amiri Serif (quotes/headings) and Cairo/Tajawal Sans-serif, borderless glassmorphism layout, and dynamic 3D mouse-tilt card physics.
