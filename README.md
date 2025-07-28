# Number Guessing Game


A simple and interactive number guessing game built with HTML, CSS (Tailwind), and JavaScript.

## Features

- **Random Number Generation**: Computer selects a random number between 1-100
- **Input Validation**: Ensures only valid numbers between 1-100 are accepted
- **Attempt Tracking**: Counts and displays number of guesses
- **Hint System**: Provides "too high" or "too low" feedback
- **New Game Button**: Restarts the game after winning
- **Keyboard Support**: Works with Enter key for quick guessing
- **Responsive Design**: Works on all device sizes

## How to Play

1. The computer selects a random number between 1 and 100
2. Enter your guess in the input field
3. Click "Guess!" or press Enter
4. Receive feedback if your guess is too high or too low
5. Keep guessing until you find the correct number
6. Click "New Game" to play again

## Technologies Used

- **HTML5**: Structure and content
- **Tailwind CSS**: Styling and responsive design
- **JavaScript**: Game logic and interactivity

## Installation

No installation required! Simply:

1. Download the `guess.html` file
2. Open it in any modern web browser
3. Start playing!

Alternatively, you can:
1. Clone the repository (if available)
2. Open the `guess.html` file in your browser

## Code Structure

```javascript
// Game initialization
function initGame() {
    // Sets up new game with random number
}

// Guess validation and checking
function checkGuess() {
    // Compares user input to secret number
    // Provides feedback
    // Tracks attempts
}

// Event listeners for:
// - Guess button click
// - Enter key press
// - New game button
