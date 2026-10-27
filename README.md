<div align="center">

# ⚗️ Breaking Bad — Interactive 3D Periodic Table Experience

An atmospheric, scroll-driven 3D animation and interactive periodic table tribute inspired by AMC's award-winning television series **Breaking Bad**.

[![Live Demo](https://img.shields.io/badge/Demo-Live%20on%20Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](#)

</div>

---

## 🧪 Overview

This project recreates the iconic **[Br]eaking [Ba]d** intro sequence using pure web technologies:
- Dynamic 3D perspective scroll animations powered by custom element detectors and tweening.
- Authentic periodic table element tiles for **Bromine (35 - Br)** and **Barium (56 - Ba)** complete with atomic weights, electron configurations, and oxidation states.
- Ambient chemical haze and smoke layering effects (`multiply` & `overlay` blend modes).
- Floating molecular formulas (`C₅H₁₀N`, `149.24`, etc.) drifting in 3D space.
- Interactive audio theme player and full-screen presentation mode.

---

## ✨ Features

- **🎬 Scroll-Driven 3D Transformations:** Responsive perspective depth zooming into element blocks as the user scrolls.
- **🌫️ Ambient Smoke & Haze:** CSS-powered multi-layer atmospheric particle smoke animations.
- **⚛️ High-Fidelity Periodic Tiles:** Faithfully styled scientific tiles displaying atomic numbers, isotopes, and electron shell distributions.
- **🔊 Audio Integration:** Embedded thematic audio controls for an immersive audiovisual experience.
- **🖥️ Fullscreen Mode:** Seamless one-click fullscreen toggle for kiosk, presentation, or showcase viewing.
- **⚡ Lightweight & Blazing Fast:** Built entirely with vanilla HTML, CSS, and JavaScript—zero build steps, zero bloated dependencies.

---

## 🗂️ Project Structure

```bash
Breaking_Bad/
├── index.html       # Primary entrypoint (optimized for Vercel & static hosting)
├── st.css           # Styling, design tokens, smoke animations & 3D perspectives
├── st.js            # Scroll-Btween engine, 3D physics tweener & audio handling
├── .gitignore       # Git ignore rules for system artifacts
└── README.md        # Project documentation
```

---

## 🚀 Getting Started Locally

No compilers or package managers required. You can run it immediately with any local static server:

### Option 1: Live Server (VS Code)
Right-click on `index.html` and select **"Open with Live Server"**.

### Option 2: Python HTTP Server
```bash
# Python 3.x
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

### Option 3: Node `npx serve`
```bash
npx serve .
```

---

## 🌐 Deploy to Vercel

### Method 1: Import via Vercel Dashboard (Recommended)

1. Go to [vercel.com](https://vercel.com) and sign in with your GitHub account.
2. Click **"Add New..."** > **"Project"**.
3. Select your repository: **`pabitralenka07/Breaking_Bad`**.
4. In the Project Configuration:
   - **Framework Preset:** `Other` (Static HTML)
   - **Root Directory:** `./`
5. Click **"Deploy"**. Your live URL will be ready in seconds!

### Method 2: Deploy via Vercel CLI

```bash
# 1. Install or run Vercel CLI directly
npx vercel

# 2. Follow the interactive prompts:
# ? Set up and deploy? [Y/n] y
# ? Which scope? (your account)
# ? Link to existing project? [N]
# ? What's your project's name? breaking-bad
# ? In which directory is your code located? ./
#
# 3. For production deployment:
npx vercel --prod
```

---

## 🎮 Controls & Interactions

| Action | Control |
| :--- | :--- |
| **Scroll Animations** | Mouse wheel / Trackpad / Arrow Keys |
| **Fullscreen** | Click `Enter FullScreen` in the top right |
| **Audio** | Toggle audio player in the bottom left menu |
| **Official Info** | Click the Breaking Bad copyright badge |

---

## 🛠️ Built With

- **HTML5** — Semantic structure, canvas layering, and audio elements.
- **CSS3** — Custom properties, keyframe animations, 3D perspective transforms, and blend modes.
- **Vanilla JavaScript** — Custom `scroll-btween` intersection observers and physics tweening.

---

## 📜 Attribution & Disclaimer

* *Breaking Bad* is a registered trademark of **Sony Pictures Television** and **AMC Network Entertainment LLC**.
* This project is a non-commercial, educational fan tribute.

---

<div align="center">
Made with 💚 by <a href="https://github.com/pabitralenka07">Pabitra Lenka</a>
</div>
