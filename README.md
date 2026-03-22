# Kota Jagadeesh – Portfolio Website

**Course**: 23AID215 – User Interface Design Lab  
**Institution**: Amrita Vishwa Vidyapeetham  
**Assignment**: Portfolio Website (15 marks)  
**Submitted by**: Kota Jagadeeshwar Reddy  

This project is a multi-page personal portfolio website developed using **HTML5** and **CSS3**.

GitHub Pages link (after deployment):  
[https://kota-jagadeesh.github.io/portfolio/](https://kota-jagadeesh.github.io/portfolio/)

## Website Structure

The website consists of **five separate HTML pages** connected via a consistent navigation menu.

| File            | Purpose                              | Main Content / Features                              |
|-----------------|--------------------------------------|-------------------------------------------------------|
| `index.html`    | Home page                  | Profile section with profile picture + ripple animation, featured projects teaser |
| `about.html`    | About me                             | Education timeline, short bio                         |
| `skills.html`   | Skills showcase                      | Colorful skill badges with hover scale & glow         |
| `projects.html` | Project gallery                      | Responsive grid with background images |
| `contact.html`  | Contact information                  | Email, GitHub, LinkedIn links + styled form appearance|

### Shared Elements (present on every page)
- Sticky navigation bar with five functional links  
  Home • About • Skills • Projects • Contact
- Footer with copyright notice

## Technologies & Implementation Details

- **HTML5** – semantic elements (`header`, `nav`, `main`, `section`, `footer`, etc.)
- **CSS3** – Flexbox, CSS Grid, custom properties, media queries, transitions, hover effects, animations (`@keyframes`), gradients, box-shadows, backdrop-filter
- Google Fonts – Poppins
- External resources – Devicon CDN (skill icons), Unsplash (background images)
- No CSS frameworks, no JavaScript libraries

### Creative Features Implemented
- Pure CSS ripple animation on profile picture (hero section)
- Smooth hover scaling + glow on skill badges
- Large project cards with visible background images + gradient overlay (home page)
- Full-screen CSS-only modal popups with project-specific backgrounds (projects page)
- Responsive layout (mobile-first + breakpoints)
- Smooth page scrolling (`scroll-behavior: smooth`)
- Gradient text titles
- Card layouts with box shadows and transitions

## Folder Structure
```md
portfolio/
├── index.html
├── about.html
├── skills.html
├── projects.html
├── contact.html
├── css/
│   └── style-core.css         (shared styles + variables)
├── images/                    (profile photo, thumbnails, modal backgrounds)
└── README.md
```

## How to View the Website Locally

1. Download or clone the repository:
   ```bash
   git clone https://github.com/Kota-Jagadeesh/portfolio.git
   ```
2. Open the folder in any code editor (VS Code recommended) 
3. Double-click index.html to open it in your browser
4. VS Code -> Live Server extension
5. Navigate between pages using the top menu
