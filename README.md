# Rohan Saburi — Personal Portfolio

> **Aspiring Software Engineer** &bull; B.Tech Computer Science &amp; Engineering, REVA University (2025&ndash;2029)  
> Based in Bengaluru, India &middot; Originally from Hyderabad, Telangana

[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-blue?style=flat&logo=github)](https://github.com/rohansaburi/rohan-saburi-portfolio)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0%20(Pure%20Vanilla)-success)](#technologies-used)

---

## 📌 Overview

This repository contains the source code for the personal portfolio website of **Rohan Saburi**. 

The portfolio is designed with a premium, restrained dark-mode aesthetic that reflects the mindset of a serious software engineer in the early stages of their career. Rather than relying on superficial statistics, percentage bars, or exaggerated claims, the site highlights authentic foundational growth across core computer science disciplines, problem solving, and practical software experimentation.

### 🌐 Live Portfolio
* **Deployment Status:** Ready for deployment to GitHub Pages.
* **Target Live URL:** `https://rohansaburi.github.io/rohan-saburi-portfolio/` *(available once enabled under repository settings)*.

---

## 🛠️ Technologies Used

* **Structure:** Semantic HTML5 (W3C standard compliant, accessible landmarks, OpenGraph & SEO tags)
* **Styling:** Modern Vanilla CSS3 (Custom design system, CSS variables, glassmorphism, responsive grid & flexbox, accessible focus rings, `prefers-reduced-motion` compliance)
* **Logic:** Vanilla JavaScript (ES6+, zero runtime dependencies, IntersectionObserver for scrollspy and smooth reveals, clipboard API with fallback)
* **Typography:** [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (display & headings), [Inter](https://fonts.google.com/specimen/Inter) (body), and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (code & technical tags)
* **Icons:** Hand-crafted, lightweight inline SVGs for maximum rendering crispness and zero HTTP overhead

---

## 📁 Project Structure

```text
rohan-saburi-portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml        # GitHub Actions automated workflow for Pages
├── assets/
│   ├── profile.jpg           # High-resolution portrait photograph
│   └── favicon.svg           # Monogram vector favicon
├── css/
│   └── style.css             # Unified design system, tokens, and responsive layout
├── js/
│   └── main.js               # Client controller (header, scrollspy, drawer, copy action)
├── .gitignore                # Git ignore rules for system and editor artifacts
├── index.html                # Master HTML document
├── package.json              # Local developer configuration & scripts
├── README.md                 # Complete documentation
└── server.js                 # Zero-dependency local development preview server
```

---

## 💻 Local Development

You can run and preview the portfolio locally with zero external package installations.

### Option 1: Using Node.js (Recommended)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rohansaburi/rohan-saburi-portfolio.git
   cd rohan-saburi-portfolio
   ```

2. **Start the local server:**
   ```bash
   npm run dev
   # or directly with Node:
   node server.js
   ```

3. Open your browser and navigate to:
   ```text
   http://localhost:3000
   ```

### Option 2: Using Any Static Server

Because this portfolio uses pure static web standards without build steps or bundlers, it can be served using any local server:

* **VS Code Live Server:** Right click `index.html` &rarr; `Open with Live Server`
* **Python (if installed):** `python -m http.server 3000`
* **Npx serve:** `npx serve .`

---

## 🚀 Deployment Instructions

### Deploying to GitHub Pages (Automated with GitHub Actions)

The repository includes a ready-to-run GitHub Actions workflow in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

1. **Push your code to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "feat: initial production portfolio release"
   git branch -M main
   git remote add origin https://github.com/rohansaburi/rohan-saburi-portfolio.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   * Go to your repository on GitHub: `https://github.com/rohansaburi/rohan-saburi-portfolio`
   * Click **Settings** &rarr; **Pages** (in the left sidebar).
   * Under **Build and deployment** &gt; **Source**, select **GitHub Actions**.
   * On your next push to `main` (or by running the workflow manually under the **Actions** tab), your site will automatically build and deploy!

3. **Verify the Live URL:**
   Once the action finishes, your portfolio will be live at:
   ```text
   https://rohansaburi.github.io/rohan-saburi-portfolio/
   ```

---

## 📬 Contact & Identity

* **Full Name:** Rohan Saburi
* **Role:** Aspiring Software Engineer
* **University:** REVA University &mdash; B.Tech Computer Science &amp; Engineering (2nd Year, Class of 2029)
* **Location:** Bengaluru, Karnataka, India (Originally from Hyderabad, Telangana)
* **Email:** [rohansaburi26@gmail.com](mailto:rohansaburi26@gmail.com)
* **GitHub:** [@rohansaburi](https://github.com/rohansaburi)
* **LinkedIn:** [linkedin.com/in/rohan-saburi](https://www.linkedin.com/in/rohan-saburi)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
