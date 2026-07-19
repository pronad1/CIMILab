# CIMILab Website

> **✨ Live Website:** [Demo](https://pronad1.github.io/CIMILab/index.html)

A fully static HTML/CSS/JavaScript website for the **Computation Informatics and Machine Intelligence Lab (CIMILab)** at the University of Missouri, MU Institute for Data Science and Informatics (MUIDSI).

## Project Quality Goals

This project is structured as a polished, academic-style research lab website with a strong first impression for prospective students, collaborators, and visitors. The design emphasizes:

- **Clarity and credibility** through concise messaging, research-focused sections, and visible lab identity.
- **Consistency** through shared layout patterns, reusable visual language, and aligned page structure.
- **Professional presentation** with polished calls to action, thoughtful content hierarchy, and a modern academic tone.
- **Accessibility and maintainability** by keeping the site static, responsive, and easy to update without a build step.

## Tech Stack

| Layer | Technology |
|---|---|
| **HTML** | Semantic HTML5 |
| **CSS** | Vanilla CSS (design system) + Tailwind CSS v3 (CDN) |
| **JavaScript** | Vanilla JS (no framework, no bundler) |
| **Fonts** | Google Fonts — Inter, IBM Plex Serif, JetBrains Mono |
| **Icons** | Inline SVG (no icon library dependency) |

```

## Running Locally

Open any `.html` file directly in your browser, **or** start a local server in this directory:

```bash
# Option 1 — Python (built-in)
python -m http.server 3000

# Option 2 — Node.js (npx serve)
npx serve .

# Option 3 — VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

Then open `http://localhost:3000` in your browser.

## Deployment

This is a pure static site — deploy anywhere:

- **GitHub Pages**: configure the repository root (`/`) as the publishing source.
- **Netlify / Vercel**: simply connect the repository without any build command.
- Any static CDN or web server.

## Updating Content

Content is embedded directly in the HTML files. To update:

| What | Where |
|---|---|
| Team members | `people.html` |
| Projects | `projects.html` + `projects/*.html` |
| Publications | `publications.html` |
| News | `news.html` + `news/*.html` |
| Lab info / contact | `contact.html`, `index.html` footer |
| Design tokens | `assets/style.css` — `:root {}` section |

## Contact

- **Email**: deycimilab@gmail.com
- **GitHub**: [github.com/CIMILab](https://github.com/CIMILab)
- **Location**: MU Institute for Data Science and Informatics, University of Missouri, Columbia, MO
