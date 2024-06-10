# Number Guesser Game

This is a simple number guessing game implemented in JavaScript. The game allows the user to input a number between 0 and 9 and guess the target number. The computer also makes a random guess. The game keeps track of the scores and round number.

## Installation

To use this game, simply clone the repository and open the `index.html` file in your web browser.

## Usage

1. Input a number between 0 and 9.
2. Click "Make a Guess" to submit your guess and see who won the round.
3. Click "Next Round" to play again.

## Code

The game consists of three files:

### `game.js`

This file contains the JavaScript code that implements the game logic. It defines the following functions:

- `generateTarget()`: Generates a random target number between 0 and 9.
- `compareGuesses(humanGuess, computerGuess, targetGuess)`: Compares the human and computer guesses to the target number and returns `true` if the human is the winner, and `false` otherwise.
- `updateScore(winner)`: Updates the score based on the winner of the round.
- `advanceRound()`: Increases the round number.

### `index.html`

This file contains the HTML structure for the game. It includes the necessary elements for displaying the round number, target number, computer and human guesses, and buttons for making guesses and advancing to the next round.

### `style.css`

This file contains the CSS styles for the game interface. It defines the layout, colors, and styles for the game elements.

## License



Feel free to contribute to this project by submitting pull requests or reporting issues. Enjoy the game!# Number-Guesser-Game
A simple number guessing game where you have to guess a number between 0 and 9. The game will keep track of the rounds played and the scores of the computer and the player.
