# Personal Portfolio

**A lightweight, responsive developer portfolio showcasing front-end projects, core skills, and contact links.**

**[Live Demo](https://shalabycode.dev/)** · **[Source](https://github.com/Shalabyelectronics/Shalabyelectronics.github.io)**

![Personal Portfolio screenshot](docs/screenshot.png)

## About

This repository contains the source code for Mohamed Shalaby's personal developer website, hosted on GitHub Pages with a custom domain (`shalabycode.dev`). Designed as a single-page portfolio, it introduces Mohamed as a self-taught front-end developer and gives an accessible overview of the technical stack. It serves as a central hub for recruiters, hiring managers, and collaborators to review the projects and get in touch.

## Features

- **Developer dark theme**: Styled with dark GitHub-inspired colors using native CSS custom properties.
- **Responsive project grid**: Displays project cards in a single column on mobile devices and expands to two columns on screens 640px and wider.
- **Featured project showcase**: Highlights key repositories with descriptions, category metadata tags, and direct links to GitHub source code.
- **Skills section**: Displays current front-end technologies as visual chips (HTML5, CSS3, JavaScript, React, APIs, and Git).
- **Contact hub**: Provides direct links to GitHub, LinkedIn, YouTube, and an email contact button.
- **Native smooth scrolling**: Navigates directly from hero action buttons to the projects section.

## Built With

- HTML5 (Semantic elements)
- CSS3 (Flexbox, CSS Grid, Custom Properties, Media Queries)
- GitHub Pages & CNAME (Static hosting and custom domain management)

## What I Learned

- Designing consistent color palettes and modular themes using CSS variables in `:root`.
- Building responsive multi-column layouts with CSS Grid and media queries without external UI frameworks.
- Structuring semantic, accessible HTML with proper metadata, smooth scrolling, and secure outbound links (`rel="noopener"`).
- Deploying a custom apex domain to GitHub Pages using a repository `CNAME` record.

## Getting Started

To run this site locally, no build step or package manager is required:

1. Clone the repository:
   ```bash
   git clone https://github.com/Shalabyelectronics/Shalabyelectronics.github.io.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Shalabyelectronics.github.io
   ```
3. Open `index.html` in your web browser, or launch it with the VS Code **Live Server** extension.

## Project Structure

```text
Shalabyelectronics.github.io/
├── CNAME          # Custom domain configuration for GitHub Pages
└── index.html     # Single-page markup, content, and inline stylesheet
```

## Roadmap

- [ ] Extract inline styles into a separate, modular CSS stylesheet.
- [ ] Add live preview links for each listed project card alongside the repository links.
- [ ] Implement a light and dark mode toggle using JavaScript and `localStorage`.
- [ ] Add dynamic project filtering by technology tag.

## Author

**Mohamed Shalaby**
- Website: [shalabycode.dev](https://shalabycode.dev)
- GitHub: [@Shalabyelectronics](https://github.com/Shalabyelectronics)
- LinkedIn: [in/mhdshalaby](https://www.linkedin.com/in/mhdshalaby/)
