# Refined Reside Realty – Frontend (Static Site)

A multi‑page responsive website built with **HTML5**, **CSS3**, and **Bootstrap 5**.  
Pages included: **Home**, **Experiences**, **Gallery**, and **Our Worlds**.

## ✨ Features
- **Responsive layout** using Bootstrap 5 grid & components
- **Reusable styles** via `css/styles.css` and page‑specific CSS
- **Branding assets** in `/images` (logos and page assets)
- **Multi‑page navigation** with a fixed‑top navbar
- **Gallery page** styled with Bootstrap utilities

## 🧱 Tech Stack
- HTML5
- CSS3
- Bootstrap 5 (CDN)

## 📂 Project Structure
```
FrontEndProject-G/
├── home.html
├── experiences.html
├── gallery.html
├── ourWorlds.html
├── css/
│   ├── styles.css
│   ├── home.css
│   ├── experiences.css
│   ├── gallery.css
│   └── ourWorlds.css
└── images/
    ├── logo.svg
    ├── logoimage.png
    ├── about/
    └── gallery/ (and other asset folders)
```

## ▶️ Run Locally
No build step required — it’s a static site.

**Option A — Open directly**
1. Double‑click `home.html` (or any page) to open in your browser.

**Option B — Serve with a simple local server (recommended)**
```bash
# Python 3
python -m http.server 8080
# then open http://localhost:8080/home.html
```

## 🔧 Customization
- Update logos and images under `/images`.
- Tweak global styles in `css/styles.css`; keep page‑specific rules in their respective CSS files.
- Replace placeholder text/titles in each page’s `<title>` and body sections.

## 🌐 Dependencies (CDN)
Bootstrap CSS is loaded via CDN in each page’s `<head>`. If you need offline use, download Bootstrap and link it locally.

## ✅ Best Practices
- Keep image sizes optimized for faster load times.
- Maintain semantic HTML and accessible alt text for images.
- Test layout on mobile and desktop viewports.

## 📄 License
MIT (or your preferred license)
