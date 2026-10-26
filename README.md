# 🎯 Guess My Number

A fun, interactive number-guessing game built using **HTML, CSS, and JavaScript**. Challenge yourself to guess a randomly generated number between 1 and 20 while trying to maintain your score!

## 🚀 Overview

Guess My Number is a browser-based game designed to practice core JavaScript concepts, including DOM manipulation, event handling, conditional statements, and random number generation.

The game provides feedback after every guess, helping players determine whether their guess is too high or too low.

## ✨ Features

- 🎲 **Random Number Generation** — Generates a secret number between 1 and 20.
- 🔍 **Interactive Guessing** — Enter a number and click *Check!* to submit your guess.
- 📈 **Instant Feedback** — Get hints indicating whether your guess is too high or too low.
- 🏆 **Score Tracking** — Start with 20 points and lose one point for each incorrect guess.
- 🥇 **High Score** — Tracks your best score during the current page session.
- 🎉 **Visual Feedback** — The background turns green when you guess correctly.
- 🔄 **Replay Option** — Start a new round using the *Again!* button.
- ⚠️ **Input Validation** — Displays a message when no number is entered.

## 🛠️ Technologies Used

- **HTML5** — Structures the game's interface.
- **CSS3** — Styles the layout, typography, buttons, and game elements.
- **JavaScript (ES6+)** — Implements game logic, event listeners, DOM manipulation, and score management.

## 🎮 How to Play

1. Open the game in your browser.
2. Enter a number between 1 and 20.
3. Click **Check!** to submit your guess.
4. Follow the hints:
   - 📈 Too high — Try a smaller number.
   - 📉 Too low — Try a larger number.
   - 🎉 Correct Number — You win!
5. Avoid incorrect guesses to preserve your score.
6. Click **Again!** to start a new round.

## 📂 Project Structure

```text
guess-my-number/
├── index.html
├── projectOneScript.js
└── README.md
```

- `index.html` — Contains the HTML structure and CSS styling.
- `projectOneScript.js` — Contains the game logic and event-handling functionality.
- `README.md` — Documents the project, features, and instructions.

## 💻 Getting Started

### Prerequisites

A modern web browser such as Google Chrome, Microsoft Edge, or Firefox.

### Installation

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd guess-my-number
   ```

3. Open `index.html` in your browser.

No additional dependencies or installation steps are required.

## 🧠 JavaScript Concepts Practiced

- `Math.random()` and `Math.trunc()` for generating random numbers.
- `document.querySelector()` for selecting and accessing DOM elements.
- `addEventListener()` for handling button clicks.
- `textContent` and `value` for reading and updating element content.
- Conditional statements (`if`, `else if`, `else`) for game logic.
- Functions for reusable message updates.
- Variables for managing the secret number, score, and high score.
- Ternary operators for displaying contextual hints.
- DOM styling for dynamic visual feedback.

## 🔮 Future Improvements

- Add keyboard support so players can submit guesses using Enter.
- Prevent additional guesses after the game ends.
- Persist the high score using `localStorage`.
- Add difficulty levels with different number ranges.
- Improve the interface with responsive styling and animations.
- Add sound effects and a restart confirmation.

## 📌 Learning Objective

This project demonstrates how JavaScript can make a static webpage interactive by responding to user input, updating the DOM dynamically, and managing application state.

---

**Built as a hands-on JavaScript learning project.**
