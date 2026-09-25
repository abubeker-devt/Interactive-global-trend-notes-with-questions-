# 🌍 Global Trends — Interactive Study Notes v1.0

A responsive, browser-based interactive quiz and study companion for the Global Trends course, built with HTML, CSS, and JavaScript.

## 🌐 Live Demo

https://abubeker-devt.github.io/Interactive-global-trend-notes-with-questions-/

## 👨‍💻 Developer

**Abubeker Muhidin Seid**

Earth Sciences student at Addis Ababa University and Web Development student at Rise Up Tech Solutions.

## ✨ Features

### 📚 Unit Coverage
- 🗂️ 5 full units — International Relations, Foreign Policy & Diplomacy, International Political Economy, Globalization & Regionalism, and Major Contemporary Global Issues
- 📝 Final Exam practice tab
- 🔢 250+ questions across the whole site

### ❓ Question Types
- ☑️ Multiple choice — tap an option to check it instantly
- 🟩 Correct answers highlight green
- 🟥 Wrong picks highlight red, with the right answer revealed alongside
- 💬 Auto-shown explanation after every MCQ attempt
- ✍️ Explain / writing questions with a tap-to-reveal model answer

### 🎨 Interface
- 🌗 Automatic light/dark theme, matching system preference
- 📱 Fully responsive — desktop and mobile friendly
- 🧭 Simple tab navigation between units and the final exam
- 🪶 Clean, distraction-free reading layout

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- No frameworks, no build tools, no dependencies

## 🚀 Run

Open `index.html` in a browser.

No framework.
No build step.

## 🌐 Deploy on GitHub Pages

1. Push this repo to GitHub (public).
2. Go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — your live URL will be `https://yourusername.github.io/repo-name/` within a minute or two.

## ✏️ Editing Content

All questions live in a single JSON object near the top of the `<script>` tag in `index.html`. Each unit has an `mcq` array (`q` question, `o` options, `a` correct answer index, `e` explanation) and an `explain` array (`q` question, `a` model answer). Edit directly and re-upload to update the site.

## 📌 Project Status

Ongoing personal study project. More units, questions, and features may be added over time.

## 🧱 Project Structure

```text
global-trends-quiz/
└── index.html
```
