# 🎮 Hangman Game

_A modern take on the classic word‑guessing game, now as a Progressive Web App (PWA)!_

![Hangman Banner](https://img.icons8.com/color/96/000000/hangman.png)

---

## 🚀 Features

- 🎯 **Single Player & Two Player Modes**
- 📊 **Scoring System**
  - Points scale by difficulty (Easy, Medium, Hard)
  - Correct letters earn points
  - Hints cost points after the first free one
- 🏆 **Leaderboard**
  - Persistent using `localStorage`
  - Separate boards for each difficulty
  - Top 10 scores saved per difficulty
- ⏱️ **Timed Mode**
  - Win before the timer runs out for bonus points
- 🌙 **Dark / Light Mode**
  - Dark mode default **ON**
  - Toggle available anytime
- 🔊 **Sound Effects**
  - Toggle sound effects (default **OFF**)
- 📱 **Responsive Layout**
  - Desktop: text input with Enter support
  - Mobile: full on‑screen QWERTY keyboard (always 3 rows)
  - Game is always centered and fixed on mobile—no scrolling

---

## 🖥️ Gameplay

1. **Enter your name** in the lobby.
2. **Choose:**
   - Difficulty: 🟢 Easy, 🟡 Medium, 🔴 Hard
   - Series length: Best of 1, 3, or 5
   - Game mode: Single Player or Two Player
3. **Play by guessing letters:**
   - **Desktop:** Type a letter + press Enter or click Guess
   - **Mobile:** Tap the on‑screen keyboard
4. **Win** by revealing the full word before you run out of lives.
5. **Scores** update instantly in the HUD and Leaderboard.

---

## 🧩 Word Bank

- The game supports a large, customizable word bank.
- Words are separated into **Easy**, **Medium**, and **Hard** for balanced gameplay.
- _Sample:_
  ```js
  const wordBanks = {
    easy: ['animal', 'basket', 'button', ...],
    medium: ['october', 'quiver', 'iguana', ...],
    hard: ['champion', 'astronaut', 'javascript', ...]
  };

Expand this to 1000+ words for more variety!
🐍 Original Python Version
This project began as a simple console Python script:

stages = [
    " +---+\n |   |\n     |\n     |\n     |\n     |\n=========",
    " +---+\n |   |\n O   |\n     |\n     |\n     |\n=========",
    " +---+\n |   |\n O   |\n |   |\n     |\n     |\n=========",
    " +---+\n |   |\n O   |\n/|   |\n     |\n     |\n=========",
    " +---+\n |   |\n O   |\n/|\\  |\n     |\n     |\n=========",
    " +---+\n |   |\n O   |\n/|\\  |\n/    |\n     |\n=========",
    " +---+\n |   |\n O   |\n/|\\  |\n/ \\  |\n     |\n========="
]

It was upgraded into this interactive PWA for a polished user experience.

📱 Mobile Experience
The game is centered and fixed on all mobile devices.
No scrolling required—everything fits and is accessible.
The on-screen keyboard is always three QWERTY rows.
📌 Roadmap
🌐 Add support for multiplayer over network
📚 Expand word bank to 1000+ words
🏅 Achievements for streaks and high scores
📜 License
MIT License — Free to use, modify, and share.

🙌 Credits
Icons8 for icons
Pixabay for free sound effects
Enjoy playing and learning with Hangman!

