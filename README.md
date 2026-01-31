# Hi Zaki | Personal Portfolio Website

![Project Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34E26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

> A minimal, interactive personal portfolio website designed for a Project Manager & Amateur Photographer based in Shanghai.

### 👉 [Visit Website: zakimao.com](https://zakimao.com)

<img width="3809" height="1912" alt="image" src="https://github.com/user-attachments/assets/8f37f5a4-b853-4175-bd1f-3cbc0b6d9b7d" />

---

## 🖼️ Preview

## ✨ Key Features

This portfolio is built with vanilla HTML, CSS, and JavaScript, focusing on performance, smooth animations, and responsive design.

### 🎨 Design & UI
* **Valorant-Inspired Hero**: The core visual interaction—a "Drum" style rolling text animation (Hello, Bonjour, 你好...) paired with a static, bold identifier—is designed as a homage to the **Valorant Agent PV / Character Select** aesthetic. It creates a dynamic yet focused introduction.
* **Interactive Atmosphere**: Background blobs in the Hero section react to mouse movement, creating a subtle parallax effect.
* **Typography**: Carefully paired fonts using *Juana* (Custom Serif) for headings and *Inter* for body text.

### 🎨 Color Palette
The site uses a specific set of colors to create a warm, immersive transition from cool digital tones to warm analog vibes.

| Usage | Color | Hex Code | Visual |
| :--- | :--- | :--- | :--- |
| **Hero Background** | Almond White | `#FAF5EF` | ⚪ |
| **Hero Blobs (Glow)** | Cyan / Teal / Sky | `#A5F3FC`, `#CCFBF1`, `#E0F2FE` | 🔵 |
| **Content Background** | Peach Puff | `#FFDAB9` | 🟠 |
| **Accent / Text** | Vermilion Red | `#E34234` | 🔴 |

### 📱 Responsive & Interactive
* **Mobile-First Adaptation**:
    * **Gallery**: Transforms from a stacked card pile on desktop to a smooth horizontal scroll snap on mobile.
    * **Hero Layout**: Adapts from a split layout to a centered vertical layout for better readability on small screens.
* **Social Hub**: A clean, grid-based social media connector section.
* **Project Showcase**: A structured display for professional projects (Figma plugins, AI agents, etc.).

### 📝 Blog System
* **Lightweight CMS**: A simple JavaScript-based blog rendering system (`posts.js`). No database required—just add a JSON object to publish a new post.

---

## 🛠️ Built With

* **Core**: HTML5, CSS3 (Flexbox & Grid), Vanilla JavaScript
* **Design**: Custom CSS Variables, CSS Animations (`@keyframes`)
* **Icons**: SVG Icons (Lucide/Custom)
* **Fonts**: J-Extralight (Custom), Inter (Google Fonts), Noto Serif SC (Google Fonts)

---

## 🚀 Getting Started

To run this project locally:

1.  **Clone the repo**
    ```bash
    git clone [https://github.com/Zaki-Mao/zaki-portfolio.git](https://github.com/Zaki-Mao/zaki-portfolio.git)
    ```
2.  **Open the folder**
    Navigate to the project directory.
3.  **Run**
    Simply open `index.html` in your browser.

---

## 📂 File Structure

```text
/
├── index.html          # Main entry point
├── style.css           # Global styles and responsive rules
├── blog/
│   ├── posts.js        # Blog data configuration
│   └── beholmes.html   # Individual blog post pages
├── images/             # Assets folder
│   ├── me.jpg
│   ├── photo/          # Gallery images
│   └── ...
└── README.md
