# rock-paper-scissor

https://theshikharpurwar.github.io/rock-paper-scissor/



This JavaScript file forms the foundation of a basic Rock, Paper, Scissors game. Here's a quick rundown of its operation:

Score Tracking: The game records the count of victories, defeats, and draws. The score is saved in the browser's local storage, enabling it to be maintained over several sessions.

Game Mechanics: The playGame function is the primary function that manages the game rules. It accepts a player's choice (rock, paper, or scissors) and contrasts it with the computer's choice, which is chosen by the pickComputerMove function (not included in the provided code). The game adheres to the conventional Rock, Paper, Scissors rules:

Rock overcomes Scissors
Scissors cut Paper
Paper covers Rock
Outcomes: The outcome of each round (win, loss, or draw) is decided based on the player's choice and the computer's choice. The outcome is then saved in the result variable.

Please be aware that the updateScoreElement and pickComputerMove functions are not included in the provided code. The updateScoreElement function is likely in charge of refreshing the user interface with the current score, and the pickComputerMove function is likely in charge of selecting the computer's move