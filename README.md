# TIC-TAC-TOE

Let's create a simple tic tac toe game in JavaScript.

_We are going to use HTML to create the game board, CSS to create the game board's style, and use JavaScript to control the game.
There are many different types of games we have. The mobile game, desktop games, web games, etc. Here we are going to create a web game that can be played on the web using the browser.

❌❌❌
⭕⭕⭕

Tic Tac Toe is a simple well known game. It is played by two players on a 3x3 grid.

Players get their own symbol, either X or O. They have to fill in a square with their symbol on the grid when it's their turn.

The goal of the game is to get three in a row. The first player to get three in a row wins.

For a quick look here is our tic tac toe game:


### JavaScript Code For Tic Tac Toe
To start with writing logic for the game first take an overview of what we are going to do.

> Select all the necessary elements from the DOM. For example, cells, result, and turn counter.

> Set 'X' and 'O' as the first player and second player. Also, create an array named board to store the values of the cells.

> Start the game and attach an onclick event to each cell.

>Onclick cells will call a function that will assign the value to the cell, change the turn, store the value in the array board and check if the player won or not.

>If the player won then show the result and disable all the cells.
