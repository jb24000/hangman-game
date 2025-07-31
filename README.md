# 🎮 Hangman Game (Classic Hybrid Edition)

This project started as a **simple Python console game** and has grown into a **user‑friendly, mobile‑ready web app**.  
The goal was to make Hangman playable not only on desktop but also seamlessly on mobile devices, without the screen shifting when the keyboard appears.  

---

## 🐍 Original Python Console Version

The very first version of this game was a Python terminal app.  
It looked something like this:

+---+ |   | O   | /|\  | / \  | |

Guess a letter: _

It was simple, text‑based, and played entirely in the terminal.

---

## 🚀 Features of the Web Upgrade

- **Classic Hangman Style**  
  Includes the traditional ASCII art gallows and stick figure that updates with each wrong guess.

- **Hybrid Input System**  
  - **Desktop:** Type guesses into an input box.  
  - **Mobile:** Enjoy a responsive, onscreen **3‑row QWERTY keyboard** that prevents the soft keyboard from moving the app around.

- **Responsive Mobile Design**  
  The custom keyboard buttons resize dynamically to fit the screen width, making it easy to play on any device.  

- **2‑Player Mode (Same Device)**  
  - Player 1 secretly types a word (hidden with •).  
  - Player 2 guesses using the normal gameplay screen.  
  - Swap roles for extra fun!

- **PWA Ready**  
  Installable on mobile devices for offline play, with a native‑app feel.

- **Preserved Core Word Bank**  
  The full ~300 word list from the Python version is included for Single Player mode.

---

## 📱 Why This Upgrade?

Originally, this was a **console‑based Python Hangman game**. While fun, it wasn’t very user‑friendly for casual play.  
The vision was to bring it to the web and make it:
- **Accessible** to players on both desktop and mobile.  
- **Stationary** on mobile (no screen shifting when typing).  
- **Classic** in style, preserving the nostalgia of Hangman.  
- **Social**, with a new 2‑Player mode for friends to play together.  

---

## 🛠️ Tech Stack
- **HTML5** + **CSS3** for layout and styling  
- **JavaScript (Vanilla)** for game logic  
- **Progressive Web App (PWA)** support for offline play and installability  

---

## 🎯 How to Play
1. Open the app in your browser (desktop or mobile).  
2. Choose a mode:
   - **Single Player:** The app picks a random word from the built‑in word bank.  
   - **2‑Player Mode:** Player 1 enters a secret word; Player 2 tries to guess.  
3. **Desktop:** Enter a letter in the input box and click **Guess!**  
4. **Mobile:** Tap letters on the custom onscreen keyboard.  
5. Correct guesses fill in the word; wrong guesses draw parts of the hangman.  
6. Win by guessing the word before the hangman is complete.  

---

## 📌 Future Ideas
- Add themes (light/dark mode).  
- Score tracking across games.  
- Online multiplayer using AWS/Firebase.  

---

⚡ From **a simple Python console game** → to a **modern, responsive, PWA‑ready Hangman app with Single & 2‑Player Modes**.
