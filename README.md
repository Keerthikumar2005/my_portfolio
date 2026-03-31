# Keerthi — Personal Portfolio Website

> A dark, modern AI/ML developer portfolio built with pure HTML, CSS & Vanilla JavaScript.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-00d4aa?style=flat-square)
![Tech](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-0094ff?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-f0c040?style=flat-square)

---

## 📸 Overview

A fully responsive, single-page personal portfolio for **Keerthi**, a final-year AI & Machine Learning student at KSR College of Technology. The portfolio showcases projects, internships, certifications, and achievements in a clean dark-themed layout with smooth animations.

---

## ✨ Features

- **Custom Animated Cursor** — dot + ring cursor with smooth lag effect
- **Scroll Reveal Animations** — elements fade and slide up as you scroll
- **Animated Skill Bars** — progress bars animate into view on scroll
- **Sticky Navigation** — blurred glass nav activates on scroll
- **Terminal Hero Card** — animated Python class card in the hero section
- **Responsive Design** — fully mobile-friendly across all screen sizes
- **Zero Dependencies** — no frameworks, no libraries, pure HTML/CSS/JS

---

## 🗂️ Sections

| Section | Description |
|---|---|
| Hero | Name, tagline, stats, CTA buttons, terminal card |
| About | Brief personal bio |
| Skills | 8 skills with animated progress bars |
| Projects | 3 ML projects with metrics and tags |
| Experience | 2 internships with highlights |
| Achievements | 4 awards and recognitions |
| Certifications | 4 professional certifications |
| Contact | Email, phone, LinkedIn, GitHub links |

---

## 🚀 Getting Started

No build tools or dependencies required.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
```

### 2. Open in browser

```bash
# Simply open the file directly
open keerthi_portfolio.html

# Or use a local dev server (recommended)
npx serve .
# or
python -m http.server 8000
```

### 3. View at

```
http://localhost:8000/keerthi_portfolio.html
```

---

## 🛠️ Customization

### Update personal info

Open `keerthi_portfolio.html` and find the following sections to edit:

**Contact links** — search for `href="#"` and replace with real URLs:

```html
<!-- LinkedIn -->
<a class="contact-item" href="https://linkedin.com/in/your-profile">

<!-- GitHub -->
<a class="contact-item" href="https://github.com/your-username">

<!-- Resume download -->
<a class="btn btn-primary" href="your-resume.pdf">
```

**Project GitHub links** — update each project card's `project-link` anchors.

### Change accent color

All colors are defined as CSS variables at the top of the `<style>` block:

```css
:root {
  --accent:  #00d4aa;  /* primary teal */
  --accent2: #0094ff;  /* blue */
  --accent3: #ff6b6b;  /* red (reserved) */
  --gold:    #f0c040;  /* achievements */
}
```

### Add a new project

Copy and paste a project card block inside `.projects-grid` and update the content:

```html
<div class="project-card reveal">
  <div class="project-num">Project — 04</div>
  <div class="project-title">Your Project Title</div>
  <p class="project-desc">Short description of what you built and how.</p>
  <div class="project-metric">⭐ Key metric here</div>
  <div class="project-tags">
    <span class="tag">Tool 1</span>
    <span class="tag">Tool 2</span>
  </div>
  <div class="project-links">
    <a class="project-link" href="#">⎔ GitHub</a>
  </div>
</div>
```

---

## 📁 File Structure

```
portfolio/
│
├── keerthi_portfolio.html   # Main portfolio file (all-in-one)
└── README.md                # This file
```

> All CSS and JavaScript are embedded inside the HTML file — no separate files needed.

---

## 🎨 Design System

| Element | Value |
|---|---|
| Background | `#060a0f` |
| Surface | `#111820` |
| Accent (Teal) | `#00d4aa` |
| Accent (Blue) | `#0094ff` |
| Text | `#e8f0f8` |
| Muted | `#6b8299` |
| Display Font | Playfair Display |
| Mono Font | DM Mono |
| Body Font | Outfit |

---

## 📬 Contact

**Keerthi**
- 📧 [keerthi200329@gmail.com](mailto:keerthi200329@gmail.com)
- 📱 +91 93608 24141
- 🔗 [LinkedIn](https://linkedin.com/in/your-profile)
- 🐙 [GitHub](https://github.com/your-username)

---

## 📄 License

This project is open source under the [MIT License](LICENSE). Feel free to use it as a template for your own portfolio — a credit link back is appreciated but not required.

---

<p align="center">Built with ❤️ & Python — © 2026 Keerthi</p>
