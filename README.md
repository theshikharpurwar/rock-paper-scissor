# rock-paper-scissor

https://theshikharpurwar.github.io/rock-paper-scissor/



This JavaScript file is the core of a simple Rock, Paper, Scissors game. Here's a brief overview of how it works:

1. **Score Keeping**: The game keeps track of the number of wins, losses, and ties. The score is stored in the local storage of the browser, allowing the score to persist across multiple sessions.

2. **Gameplay**: The `playGame` function is the main function that handles the game logic. It takes in a player's move (rock, paper, or scissors) and compares it to the computer's move, which is determined by the `pickComputerMove` function (not shown in the provided code). The game follows the standard rules of Rock, Paper, Scissors:

    - Rock beats Scissors
    - Scissors beat Paper
    - Paper beats Rock

3. **Results**: The result of each game (win, loss, or tie) is determined based on the player's move and the computer's move. The result is then stored in the `result` variable.

Please note that the `updateScoreElement` and `pickComputerMove` functions are not shown in the provided code. The `updateScoreElement` function is presumably responsible for updating the user interface with the current score, and the `pickComputerMove` function is presumably responsible for determining the computer's move.