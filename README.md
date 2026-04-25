# Portfolio — Vishveshwara M N

> Personal portfolio website for **Vishveshwara M N** — Full Stack Developer based in Bengaluru, India.

🌐 **Live site:** [mnvishveshwara.github.io](https://mnvishveshwara.github.io/)

---

## About

This is the source code for my personal portfolio. Built as a **single self-contained HTML file** — no build step, no dependencies, no JavaScript frameworks. Just thoughtful HTML, CSS, and vanilla JavaScript, hosted on GitHub Pages.

The site showcases my work as a Full Stack Developer, with sections covering my experience, projects, technical skills, education, and contact information.

## Highlights

- **Fully responsive** — works cleanly on mobile, tablet, and desktop
- **Smooth scroll navigation** with sticky nav bar
- **Scroll-triggered reveal animations** using `IntersectionObserver`
- **Click-to-copy email** with visual feedback for cross-platform compatibility
- **Open-in-Gmail compose** link for quick outreach
- **Subtle grain overlay** and warm dark theme for visual depth
- **Accessible** — semantic HTML, respects `prefers-reduced-motion`
- **Zero external JavaScript dependencies** — loads fast, stays simple

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Behavior | Vanilla JavaScript (no frameworks) |
| Typography | Fraunces (serif) · Manrope (sans) · JetBrains Mono |
| Hosting | GitHub Pages |

## Project Structure

```
.
├── index.html                    # Entire site (HTML, CSS, JS embedded)
├── Vishveshwara_MN_Resume.pdf    # Downloadable resume
└── README.md                     # You're reading it
```

## Run Locally

No build tools required. Clone the repo and open the HTML file in any browser.

```bash
git clone https://github.com/mnvishveshwara/mnvishveshwara.github.io.git
cd mnvishveshwara.github.io

# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

## Customization

All content lives in `index.html`. To update:

- **Hero / About / Skills** — edit the corresponding `<section>` in the HTML
- **Experience** — find the `.timeline` block and edit each `.tl-item` entry
- **Projects** — find `.projects-grid` and edit each `<article class="project">`
- **Colors** — modify the CSS custom properties in the `:root` block at the top of the `<style>` tag
- **Fonts** — change the Google Fonts `<link>` in the `<head>` and update the `--serif`, `--sans`, `--mono` variables

## Connect

- 🌐 **Portfolio:** [mnvishveshwara.github.io](https://mnvishveshwara.github.io/)
- 💼 **LinkedIn:** [Vishveshwara M N](https://linkedin.com/in/vishveshwara-m-n-502792191)
- 📧 **Email:** vishveshwaranraj@gmail.com
- 📍 **Location:** Bengaluru, India

---

## License

Free to use as a reference or starting point for your own portfolio. Please don't copy it verbatim — make it yours.

---

<sub>Designed and built with care · © 2026 Vishveshwara M N</sub>
