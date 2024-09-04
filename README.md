# Number Guessing Game
==========================

Sample solution for the [number-guessing-game](https://roadmap.sh/projects/number-guessing-game) challenge from (roadmap.sh)(https://roadmap.sh).

## Introduction
---------------

Welcome to the Number Guessing Game! This is a simple command-line game where you have to guess a randomly generated number between 1 and 100. The game has three difficulty levels: Easy, Medium, and Hard, each with a different number of attempts to guess the correct number.

## How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/bharat-yadav-11/number-guessing-game.git


## How to Play
--------------

1. Run the game by executing the JavaScript file.
2. You will be presented with a welcome message and a prompt to select the difficulty level.
3. Choose the difficulty level by entering 1 for Easy, 2 for Medium, or 3 for Hard.
4. Once you've selected the difficulty level, you will be prompted to enter your guess.
5. Enter a number between 1 and 100.
6. If your guess is incorrect, you will receive a hint indicating whether the correct number is higher or lower than your guess.
7. Keep guessing until you correctly guess the number or run out of attempts.

## Difficulty Levels
-------------------

* **Easy**: 10 attempts to guess the correct number.
* **Medium**: 5 attempts to guess the correct number.
* **Hard**: 3 attempts to guess the correct number.

## Technical Details
--------------------

This game is built using Node.js and the `readline` module for handling user input. The game logic is implemented in JavaScript, and the code is organized into separate functions for each difficulty level and for handling user input.

### Requirements

* Node.js (version 14 or higher)
* `readline` module (built-in with Node.js)

### Code Structure

The code is organized into the following files:

* `index.js`: The main entry point of the game.
* `easy`, `medium`, `hard`: Separate functions for each difficulty level.
* `difficultyLevel`: A function for handling user input and selecting the difficulty level.


## Contributing
--------------

If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

### Contributing Guidelines

* Please follow the existing code style and structure.
* Make sure to test your changes before submitting a pull request.
* Keep your changes concise and focused on a single issue or feature.

## Authors
---------

* [Bharat Yadav](https://github.com/Bharat-Yadav-11)

## Acknowledgments
---------------

* Thanks to the Node.js community for providing the `readline` module.
* Thanks to the GitHub community for providing a platform for open-source projects.
* Thanks to Roadmap.sh for providing this project idea.