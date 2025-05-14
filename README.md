# EduNation 🌐🎓  
*A lightweight, database-free front-end prototype for a next-gen e-learning portal.*

---

## 🎞️ Features
- Responsive **landing page** with hero banner & CTA  
- Topic pages for **Programming, Maths, Languages, QA, Skills & Categories**  
- **Authentication stubs**: `logIn.html`, `signUp.html`  
- Smooth-scrolling navbar & basic DOM interactivity (vanilla JS)  
- Mobile-first layout using Flexbox & CSS Grid  
- SVG icons & compressed images for fast loading  
- Placeholder sections for future video lessons and tech-stack highlights  

---

## 🗂️ Pages Overview

| File | Purpose |
|------|---------|
| `index.html` | Home / hero landing |
| `aboutUs.html` | Mission & team snapshot |
| `categories.html` | High-level course taxonomy |
| `programming.html` | Coding track overview |
| `maths.html` | Mathematics track overview |
| `languages.html` | Language-learning track |
| `skills.html` | Soft-skills & employability |
| `qa.html` | Q&A / community hub (static) |
| `techUsed.html` | Stack & tooling showcase |
| `video.html` | Placeholder for future lectures |
| `logIn.html`, `signUp.html` | Auth prototypes |

---

## 🛠️ Tech Stack

| Layer | Tools |
|-------|-------|
| Mark-up | **HTML5** (semantic) |
| Styling | **CSS3** (custom vars, Grid, Flexbox) |
| Interactivity | **Vanilla JavaScript (ES6)** |
| Versioning | **Git** (full history included) |
| Assets | **SVG, PNG** |

---

## 📁 Project Structure

```
EduNation/
├─ index.html
├─ html/                 # inner pages
│   ├─ aboutUs.html
│   ├─ categories.html
│   └─ … (8 more)
├─ styles/
│   └─ mainstyle.css
├─ scripts/
│   └─ mainscript.js
├─ media/
│   ├─ images/
│   └─ videos/           # empty placeholder
└─ wireframes_webInfos/
└─ screenshots.docx
```

---

## 🚀 Getting Started
1. **Clone**
   ```bash
   git clone https://github.com/Dev-Abdelrahman-Almakhzangy/EduNation.git
   cd EduNation
   ```

2. **Serve** (any static server)
   ```bash
   npx serve .
   ```

3. Open `http://localhost:5000` (or just double-click `index.html`) and explore.

---

## 🤝 Contributing

1. Fork → create feature branch → commit → push → open PR.  
2. Please open an issue first for major proposals.

---

## 🗺️ Roadmap

- Integrate with a back-end (Node, Django or Headless CMS)
- Implement JWT auth & user CRUD
- Replace placeholder assets with real course content
- Add automated tests & CI workflow

---

## 📄 License

This project was developed for educational purposes at the British University in Egypt as part of the Principles of Web Programming course.
