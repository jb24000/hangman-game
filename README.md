🎮 Hangman Game
A modern take on the classic Hangman word‑guessing game.
Built as a Progressive Web App (PWA) so it works seamlessly on both desktop and mobile.

This project started as a simple Python Hangman script and was transformed into a fully interactive, user‑friendly web app.

🚀 Features
🎯 Single Player & Two Player Modes

📊 Scoring System

Points scale by difficulty (Easy, Medium, Hard)

Correct letters earn points

Hints cost points after the first free one

🏆 Leaderboard

Persistent using localStorage

Separate boards for each difficulty

Only the top 10 scores are saved per difficulty

⏱️ Timed Mode

Win before the timer runs out for bonus points

🌙 Dark / Light Mode

Dark mode default ON

Toggle available anytime

🔊 Sound Effects

Toggle sound effects (default OFF)

📱 Responsive Layout

Desktop: text input with Enter support

Mobile: full on‑screen keyboard

🖥️ Gameplay
Enter your name in the lobby.

Choose:

Difficulty (Easy, Medium, Hard)

Series length (Best of 1, Best of 3, Best of 5)

Game mode (Single Player or Two Player)

Play by guessing letters:

On desktop: type a letter + press Enter or click Guess

On mobile: tap the on‑screen keyboard

Win by revealing the full word before you run out of lives.

Scores update instantly in the HUD and Leaderboard.

🧩 Word Bank
The game supports a large customizable word bank.
Currently, the sample set includes a few words for testing.
You can expand this to 1000+ words for more variety.

🐍 Original Python Version
This project began as a simple console Python script:

python
Copy
Edit
stages = [
    "  +---+\n  |   |\n      |\n      |\n      |\n      |\n=========",
    "  +---+\n  |   |\n  O   |\n      |\n      |\n      |\n=========",
    "  +---+\n  |   |\n  O   |\n  |   |\n      |\n      |\n=========",
    "  +---+\n  |   |\n  O   |\n /|   |\n      |\n      |\n=========",
    "  +---+\n  |   |\n  O   |\n /|\\  |\n      |\n      |\n=========",
    "  +---+\n  |   |\n  O   |\n /|\\  |\n /    |\n      |\n=========",
    "  +---+\n  |   |\n  O   |\n /|\\  |\n / \\  |\n      |\n========="
]

word_list = ["apple", "banana", "cherry"]
It was upgraded into this interactive PWA for a polished user experience.

📌 Roadmap
Add support for multiplayer over network

Expand word bank to 1000+ words

Achievements for streaks and high scores

📜 License
MIT License. Free to use, modify, and share.
