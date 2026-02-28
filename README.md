# 🗃️ Interactive Git & GitHub Learning Simulator

A **beautiful, single-file interactive dashboard** that visually teaches Git and GitHub concepts through simulation — no real Git commands are executed.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen)

## ✨ Features

### 🎮 Interactive Git Commands
Simulate 11 Git commands with visual feedback:
- `git init` · `git add` · `git commit` · `git status` · `git log`
- `git branch` · `git checkout` · `git merge`
- `git fetch` · `git pull` · `git push`

### 📊 Visual Dashboard
- **Working Directory → Staging → Local Repo → Remote** pipeline
- Animated flow arrows showing data movement
- Color-coded file status indicators
- Real-time branch & HEAD tracking

### 🌳 Branch Graph Visualizer
- Canvas-rendered commit history
- Main and feature branch lines
- Merge connections with visual indicators
- Animated commit nodes with glow effects

### 💻 Terminal Output Panel
- Realistic terminal styling with blinking cursor
- Color-coded output (success, error, warning, info)
- Command history with timestamps

### 💡 Learning Panels
- **"What Just Happened?"** — plain-English explanations after every action
- **"Common Mistake to Avoid"** — beginner-friendly warnings
- **10 Key Concepts** — HEAD, origin, main, fetch vs pull, merge conflicts, PRs, and more

### 📖 Story Mode — Collaboration Scenarios
Walk through real-world team situations:
| Scenario | Description |
|----------|-------------|
| 1 | Alex pushes first — your push gets rejected |
| 2 | You push without pulling — rejected error |
| 3 | Both edit the same line — **merge conflict** with conflict markers |
| 4 | Both edit different files — clean auto-merge |

Each scenario shows conflict markers (`<<<<<<< HEAD`), resolved versions, and step-by-step explanations.

### 🧩 Mini Quiz
6 multiple-choice questions with instant feedback and detailed explanations covering:
- Push/pull workflows
- Fetch vs pull differences
- Merge conflicts
- Staging area purpose
- HEAD pointer
- Pull Requests

### 🎨 UI/UX
- **Dark mode** theme
- **Glassmorphism** cards with backdrop blur
- Smooth CSS animations & transitions
- Hover tooltips on all buttons
- Toast notifications
- Fully responsive layout

## 🚀 Getting Started

**No installation needed.** Just open the file in a browser:

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/git-visual-practice.git
   ```
2. Open `index.html` in any modern browser.

That's it — zero dependencies, zero build steps.

## 📁 Project Structure

```
git-visual-practice/
├── index.html   ← Entire app (HTML + CSS + JS)
└── README.md
```

## 🖥️ Usage

1. Click **`git init`** to initialize the simulation
2. Use command buttons to walk through the Git workflow
3. Watch files move across the 4 zones visually
4. Read the explanation panel to understand each step
5. Try the **Story Mode** scenarios for collaboration lessons
6. Test yourself with the **Quiz** at the bottom

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 | Structure |
| CSS3 | Styling, animations, glassmorphism |
| Vanilla JS | Simulation logic, Canvas rendering |
| Canvas API | Branch graph visualization |

**Zero external libraries. Zero CDN links. Zero frameworks.**

## 📄 License

MIT License — free to use, modify, and share.

---

<p align="center">Made with ❤️ for learning Git & GitHub</p>
