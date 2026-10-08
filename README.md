# Portfolio: Utkarsh Vaibhav

**Personal site for Utkarsh Vaibhav, full-stack and AI developer: projects, skills, experience and contact.**

[![Live site](https://img.shields.io/badge/site-live-2ea44f?logo=vercel)](https://utkarshportfoliowebsite.vercel.app)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

**Live:** https://utkarshportfoliowebsite.vercel.app

![Portfolio home section](docs/screenshots/home.png)

## Features

- Sections for about, skills (including AI and agentic AI), projects, experience and contact
- Light and dark themes: follows the system setting, with a toggle that remembers your choice
- Responsive layout with a mobile menu; no horizontal scrolling down to 320 px
- Accessible: skip link, visible focus states, labelled controls, reduced-motion support
- No build step and no framework: plain HTML, CSS and JavaScript; images served as WebP

## Getting started

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Project structure

```text
├── index.html
├── css/styles.css         # design tokens, light/dark themes, layout
├── js/main.js             # theme toggle, mobile menu, active link, scroll reveal
├── assets/
│   ├── favicon.svg
│   └── images/projects/   # project screenshots (WebP)
└── docs/screenshots/
```

## Deployment

Deployed on Vercel as a static site from the repository root (no build command).

## License

MIT. See [LICENSE](LICENSE).
