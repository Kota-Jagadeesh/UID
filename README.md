# Portfolio asignment

This is the source code for my portfolio assignment. This is built with       **HTML, CSS, and a sprinkle of Logic** to keep it fast and easily maintainable.

## Architecture

Structured this project to be modular despite being a static site. and separated the concerns into specific stylesheet.

* **`style-core.css`**: The manin css. It handles the CSS Variables (Theming), the responsive Navbar logic, and the global Layout resets.
* **`style.css`**: Home-page specific styles including the profile ripple animations and profile transitions.
* **feature-Specific CSS**: (`about.css`, `projects.css`, `contact.css`) specialized styles for the Timeline, Project Grid, and Form layouts.

## Technical Highlights

### 1. The "Checkbox" Navigation
I implemented a fully responsive mobile hamburger menu.
* **How:** by using a hidden `<input type="checkbox">` and the CSS sibling selector (`#menu-toggle:checked ~ .nav-links`). 
* **Why:** coz it reduces the "Time to Interactive" and ensures the menu works even if a user has JS disabled.

### 2. Performance-First Theming
locked this site into a **Permanent Dark Theme** (`#0f0f1a`). 
* Uses **CSS Custom Properties (Variables)** for colors and shadows, making it  easy to tweak the primary `--accent` color (#7b5eff) across the entire site in one line.
* utilised `backdrop-filter: blur()` for that modern "glassmorphism" effect on the sticky navbar.

### 3. CSS-Only Profile Ripple
The main section has a profile wrapper with a custom `@keyframes ripple` animation. This creates a pulsing depth effect on hover using stacked `box-shadows`.

### 4. Optimized Project Grids
in this the  `projects.grid` uses `grid-template-columns: repeat(auto-fit, minmax(320px, 1fr))`. means the layout **calculates itself** - it's perfectly responsive on everything from a giant monitor to a 5-year-old Android phone without needing dozens of media queries.

## Deployment
Currently optimized for **GitHub Pages**. Since it’s purely static

Want to see my original portfolio -> [kota-neon.vercel.app](https://kota-neon.vercel.app)
---
*Built with ❤️*