<div align="center">
  <img width="1200" height="475" alt="Bato's Staircase Escape" src="https://placehold.co/1200x475/1a1a2e/ff3333?text=Bato's+Staircase+Escape" />
</div>

# 🏃 Bato's Staircase Escape

A 2D pixelated endless runner game where Senator Ronald "Bato" dela Rosa runs up a never-ending staircase to evade an ICC arrest warrant. Built with HTML5 Canvas and vanilla JavaScript.

**Play live:** [https://bato-staircase-escape.vercel.app](https://bato-staircase-escape.vercel.app)

## 🎮 Game Overview

Senator Bato is inside an ominous government building. The Philippine Supreme Court has denied his appeal to block the ICC warrant. Now, ICC marshals and NBI agents are chasing him up an endless staircase. How long can you survive?

## 🕹️ How to Play

| Control | Desktop | Mobile |
|---------|---------|--------|
| Move Left | ← or A | Touch LEFT button or swipe |
| Move Right | → or D | Touch RIGHT button or swipe |
| Pause | P key | Pause button (top-right) |

**Objective:** Avoid obstacles (ICC marshals, NBI agents, ICC warrants) and collect power-ups to survive as long as possible. The game speed increases every 20 seconds.

## 📱 Mobile Features

- On-screen touch buttons (60px minimum)
- Swipe left/right anywhere on screen
- Haptic feedback (vibration on collect/obstacle)
- Orientation detection (landscape recommended)
- High score saved locally
- PWA installable to home screen

## 🖥️ Run Locally

**Prerequisites:** Any web browser (no Node.js required for basic version)

### Simple method (no server needed):
1. Download `index.html`
2. Double-click to open in your browser
3. Play immediately

### With local server (optional):
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have npx)
npx serve .
