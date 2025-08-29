# 🎮 2048 Game

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![SCSS](https://img.shields.io/badge/Styles-SCSS-pink)](https://sass-lang.com/)

A classic **2048 puzzle game** implemented using **Vanilla JavaScript (ES6)**, **HTML5**, and **SCSS**.
The project follows a modular structure with a clean architecture using classes.

---

## 📷 Preview

_(You can add a screenshot or gif of your game here)_

---

## 🚀 Live Demo

👉 [Play the game](https://your-demo-link.com)
_(Replace with your GitHub Pages / Vercel / Netlify link if deployed)_

---

## 📦 Project Structure

```
2048/
│── src/
│ ├── modules/
│ │ └── Game.class.js # Main Game logic (class-based)
│ ├── scripts/
│ │ └── main.js # Entry point, event handling, initialization
│ ├── styles/
│ │ └── main.scss # SCSS styles for the game
│ └── index.html # HTML template
├── .eslintrc.js # ESLint configuration
├── .stylelintrc.js # Stylelint configuration
├── .editorconfig # Editor configuration
├── package.json # Project metadata and dependencies
└── README.md # Project documentation
```

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/2048.git
   cd 2048

   ```

2. Install dependencies:

```

npm install
```

3. Run the project in development mode:

npm start

4. Build for production:

npm run build

🎮 How to Play

Use Arrow Keys (↑ ↓ ← →) to move tiles.

When two tiles with the same number collide, they merge into one.

Reach 2048 to win the game!

If no more moves are possible → Game Over.

🛠️ Tech Stack

JavaScript (ES6+) – game logic

HTML5 – structure

SCSS – styling

Parcel (or any bundler) – build and development

🧹 Linting & Code Style

ESLint – JavaScript linting

Stylelint – SCSS linting

EditorConfig – consistent coding style across editors

BEM methodology – for class naming in CSS

Run linters:

npm run lint:js
npm run lint:css


🎮 Enjoy The Game!!!