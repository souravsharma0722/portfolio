# Product Requirement Document (PRD)

## Project Name: Personal Portfolio Website
**Target URL:** [souravsharma0722.github.io/portfolio](https://souravsharma0722.github.io/portfolio/)  
**Primary Owner:** Sourav Sharma  
**Status:** In Development  

---

## 1. Executive Summary & Goal
The objective of this project is to build a premium, highly responsive personal developer portfolio website. The site serves as a digital resume, highlighting professional skills, showcasing key projects, and providing an interactive avenue for recruiters, clients, and collaborators to make contact.

---

## 2. Target Audience
- **Tech Recruiters:** Looking for technical capabilities, resume details, and clean presentation.
- **Potential Clients:** Looking for previous work, reliability, and modern web design standards.
- **Developer Community:** Looking for open-source contributions, code quality, and engineering patterns.

---

## 3. Core Features
- **Hero & Intro:** Engaging headline introducing Sourav, descriptive CTA to view projects/resume, and subtle aesthetic background.
- **Skills Matrix:** Dynamic presentation of frontend, backend, tools, and databases with interactive visual feedback.
- **Projects Showcase:** Grid of featured projects including titles, short descriptions, technology badges, and links to GitHub / Live demos.
- **Contact & Footer:** Clean submission/contact layout with links to professional networks (LinkedIn, GitHub, Email).

---

## 4. Design & Aesthetics Specifications
- **Harmonious Color Palette:** Custom HSL variables defining sleek, dark-themed palettes.
- **Modern Typography:** Styled with professional typeface pairings (e.g., Outfit/Inter font families).
- **Glassmorphism:** Frosted border structures, glowing ambient backdrops, and blur filters.
- **Micro-Animations:** Fluid transitions, scale-up hover states on project cards, and active navigation indicators.

---

## 5. Technical Requirements
- **Framework:** Astro (Static Site Generator) for maximum speed and zero-JS-by-default performance.
- **Styling:** Vanilla CSS structure (defined centrally inside `src/styles/index.css`) for high maintainability.
- **Hosting:** GitHub Pages via GitHub Actions.
- **SEO & Accessibility:** Descriptive title tags, meta description, HTML5 semantic layout (`<header>`, `<main>`, `<section>`, `<footer>`), and accessible ARIA attributes.

---

## 6. Future Enhancement Roadmap
- **Blog Section:** Markdown/MDX-driven blog for technical writing.
- **Light/Dark Theme Toggle:** LocalStorage-persisted theme switcher.
- **Performance Analytics:** Privacy-friendly website analytics integration.
