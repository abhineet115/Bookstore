# 📚 Online Bookstore Website

A clean, responsive, and modern eCommerce static web application for an online bookstore featuring curated book collections, individual product detail pages, ratings, pricing, and shopping interactions.

[![Deploy to GitHub Pages](https://github.com/abhineet115/Bookstore/actions/workflows/deploy.yml/badge.svg)](https://github.com/abhineet115/Bookstore/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-2ea44f?style=flat-square&logo=github)](https://abhineet115.github.io/Bookstore/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 🌐 Live Demo

The website is deployed and hosted on GitHub Pages:

👉 **[https://abhineet115.github.io/Bookstore/](https://abhineet115.github.io/Bookstore/)**

---

## ✨ Features

- 📖 **Featured Books Catalog**: Curated selection of 18 popular books across self-improvement, finance, psychology, fiction, and business.
- 🔍 **Dedicated Book Detail Pages**: Individual product showcase pages (`pages/book1.html` – `pages/book18.html`) featuring book synopses, publication specifications, ISBNs, prices, and customer ratings.
- 💡 **Related Book Recommendations**: Smart recommendation cards on book detail pages.
- 📱 **Fully Responsive Layout**: Mobile-friendly navigation and flexible grid system supporting desktops, tablets, and smartphones.
- ⚡ **Zero External Asset Lag**: All image assets (covers, logos, icons) are bundled locally in the repository for ultra-fast loading.
- 📬 **Contact & About Sections**: Built-in contact form and company story sections.

---

## 📁 Project Structure

```
Bookstore/
├── .github/
│   └── workflows/
│       └── deploy.yml          # Automated GitHub Pages CI/CD workflow
├── images/                     # Local image repository
│   ├── BOOKSTORE-LOGO-removebg-preview.png
│   ├── cart.png
│   ├── book1.png               # Atomic Habits
│   ├── book2.png               # The Psychology of Money
│   ├── ...                     # book3.png through book18.png
│   └── book18.png
├── pages/                      # Product detail pages
│   ├── book1.html
│   ├── book2.html
│   ├── ...                     # book3.html through book18.html
│   ├── book18.html
│   └── style1.css              # Stylesheet for detail pages
├── index.html                  # Main landing page
├── style.css                   # Primary stylesheet
├── README.md                   # Project documentation
└── read.md                     # Documentation alias
```

---

## 🚀 Getting Started Locally

### Prerequisites
Any standard web browser or local HTTP server (Python, Node.js, VS Code Live Server).

### Option 1: Python HTTP Server (Recommended)
```bash
# Clone the repository
git clone https://github.com/abhineet115/Bookstore.git
cd Bookstore

# Start local server on port 3000
python -m http.server 3000
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 2: Node.js `serve` / `npx http-server`
```bash
npx serve .
# OR
npx http-server -p 3000
```

### Option 3: Direct File Open
You can also open [index.html](file:///c:/Users/CODE15/Documents/GitHub/Bookstore/index.html) directly in any web browser.

---

## ⚙️ GitHub Pages Setup

This repository is configured for automatic deployment to GitHub Pages via GitHub Actions:

1. Go to your GitHub repository: `https://github.com/abhineet115/Bookstore`
2. Navigate to **Settings** > **Pages**
3. Under **Build and deployment**:
   - **Source**: Select **GitHub Actions** (or select **Deploy from a branch** -> `main` / `/(root)`)
4. The site will be automatically published at:
   ```
   https://abhineet115.github.io/Bookstore/
   ```

---

## 🛠️ Built With

- **HTML5** – Semantic markup
- **CSS3** – Custom styling, Flexbox & Grid layouts, transitions
- **FontAwesome** – Icons and typography
- **GitHub Pages & Actions** – Automated static site hosting & CI/CD

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
