# 🎮 Tic-Tac-Toe vs Unbeatable AI

**▶️ Play live: [arjinder111.github.io/tic-tac-toe](https://arjinder111.github.io/tic-tac-toe)**

A browser Tic-Tac-Toe game with an AI opponent that never loses, plus a local 2-player mode.

## Features
- 🤖 **Unbeatable AI** using the Minimax algorithm: it explores every possible future move and always picks the best one
- 👥 **2-player mode** on the same device
- Score tracking, win highlighting and smooth animations
- Fully responsive, works on mobile
- Zero dependencies: a single HTML file with vanilla JavaScript

## How the AI works
For every empty cell, the AI simulates the rest of the game recursively and scores each outcome
(win = positive, loss = negative, draw = 0). Faster wins score higher and slower losses score less badly,
so the AI wins as quickly as possible and blocks every threat.

## Tech
HTML · CSS · Vanilla JavaScript · GitHub Pages

## Run locally
Just open `index.html` in any browser.

---
Built by [Arjinder Singh](https://github.com/arjinder111)
