# 🚀 Sourav Sharma - Developer Portfolio

A premium, responsive developer portfolio website built using Astro and modern CSS design systems. 

**Live Demo:** [souravsharma0722.github.io/portfolio](https://souravsharma0722.github.io/portfolio/)

---

## 🛠️ Tech Stack & Architecture

- **Framework:** [Astro](https://astro.build/) (Static Site Generator for optimal speed and SEO)
- **Styling:** Vanilla CSS (Custom properties, grid systems, HSL-tailored colors, and glassmorphism)
- **Deployment:** GitHub Pages (Automated via GitHub Actions)

---

## ✨ Features

- **Responsive Grid:** Tailored layouts for Mobile, Tablet, and Desktop.
- **Modern Typography:** Styled with professional and sleek typography pairings.
- **Interactive Showcases:** Fully browsable project cards, interactive skills matrix, and contact form/social highlights.
- **Premium Aesthetics:** Curated color schemes with smooth hover effects, micro-animations, and glass-like components.
- **High Performance:** 100/100 Lighthouse score potential due to Astro's zero-JS-by-default architecture.

---

## 🧞 Commands

All commands are run from the `portfolio` subdirectory:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs project dependencies |
| `npm run dev` | Starts local dev server at `localhost:4321` |
| `npm run build` | Builds your static site to `./dist/` |
| `npm run preview` | Previews the build locally before deploying |

---

## 📦 Project Structure

```text
portfolio/
├── .github/workflows/deploy.yml  # GitHub Actions deploy script
├── public/                       # Static assets (images, icons)
├── src/
│   ├── components/               # Astro UI Components (Hero, Skills, Projects, Footer, etc.)
│   ├── layouts/                  # Base Layout configuration
│   ├── pages/                    # Site pages (index.astro)
│   └── styles/                   # Core CSS files (index.css)
├── astro.config.mjs              # Astro configuration
└── package.json                  # Dependencies and scripts
```

---

## 🚀 Deployment Guide

This project is configured to auto-deploy to GitHub Pages using GitHub Actions.

1. **Push your code** to the `main` branch of your GitHub repository.
2. In your repository on GitHub, navigate to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, choose **GitHub Actions**.
4. The site will compile and deploy automatically on every push!
