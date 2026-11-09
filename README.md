# Project: Rock Paper Scissors 

This is my third project as part of the **Foundations** course in **The Odin Project** curriculum. 

## Live Preview
[Play the Game Here](https://awan921.github.io/Project-ROPS/) 

## Project Overview
The goal of this project was to build a classic Rock Paper Scissors game that runs entirely in the browser. It started as a console-based game using `prompt()` and `console.log()`, and was later refactored to include a fully interactive User Interface (UI) using DOM manipulation.

## Skills Demonstrated
- **HTML5:** Semantic structuring of the game board, buttons, and result area.
- **CSS3:** Custom dark theme styling, hover effects, Flexbox for centering, and smooth transitions.
- **JavaScript Fundamentals:**
  - Writing reusable functions (`getComputerChoice`, `playRound`).
  - Using `Math.random()` to generate random computer choices.
  - Implementing game logic with `if/else` statements.
  - Using `for` loops to manage the 5-round game structure.
  - Managing global state (variables for scores and rounds played).
- **DOM Manipulation:**
  - Selecting HTML elements using `document.getElementById()`.
  - Attaching Event Listeners (`addEventListener`) to buttons.
  - Dynamically updating HTML content using `.innerText` and template literals.
- **Git & GitHub:** Making atomic commits and pushing to a remote repository.

## Game Rules
1. The game is played for exactly **5 rounds**.
2. You play against the computer.
3. Rock beats Scissors, Scissors beats Paper, and Paper beats Rock.
4. The first to win the most rounds out of 5 is declared the overall winner.