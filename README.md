# ✦ PulseFlow Analytics — Responsive Landing Page

A modern, responsive, and performance-focused landing page built strictly with **Semantic HTML5** and **Modern CSS3**. Developed as part of a Web Development Internship assignment.

---

## 📌 Project Overview

**PulseFlow Analytics** is a SaaS-style landing page designed to demonstrate modern web layout standards without relying on third-party frameworks or JavaScript. The interface includes a full navigation bar with a pure-CSS mobile toggle, a conversion-focused hero section with an analytical preview card, feature/service grids, a call-to-action block, and a structured multi-column footer.

- **Live Demo:** [Add your deployed URL here, e.g., GitHub Pages / Netlify / Vercel]
- **Repository:** [Add your repository URL here]

---

## ✨ Features

- **100% Pure HTML & CSS:** No JavaScript, Bootstrap, Tailwind, or external layout dependencies.
- **Pure-CSS Responsive Navigation:** Fully functional hamburger menu on mobile screens built using the CSS checkbox technique and CSS transitions.
- **Fluid Multi-Device Layout:**
  - Optimized for **Desktop** (>992px), **Tablet** (768px–992px), and **Mobile** (<768px & <480px).
  - Strict horizontal overflow control (`overflow-x: hidden` with `box-sizing: border-box`).
- **Modern Layout Engines:**
  - **CSS Flexbox:** Applied to single-axis components (nav items, action buttons, metrics counters, form fields).
  - **CSS Grid:** Applied to two-dimensional structures (hero split, 3-column feature cards, 4-column footer).
- **Design Tokens via CSS Variables:** Centralized color palette, typographic scales, spacing tokens, and border radii in `:root`.
- **Pure-CSS UI Visual:** Interactive-looking dashboard card with custom pure-CSS bar charts, status badges, and subtle hover interactions.
- **Accessibility (a11y):**
  - Fully semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
  - Screen-reader accessible hidden labels (`.sr-only`).
  - High-contrast text colors meeting WCAG AA accessibility standards.
  - Clear `:focus-visible` styling for keyboard navigation.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic structure, document metadata, and accessible DOM tree |
| **CSS3** | Flexbox, Grid, Custom Properties (`:root`), Media Queries, Transitions |

---

## 📂 Project Structure

```text
landing-page-project/
│
├── index.html        # Semantic HTML5 markup
├── style.css         # Modular CSS stylesheet
└── README.md         # Project documentation and setup guide# task1elevatlabs