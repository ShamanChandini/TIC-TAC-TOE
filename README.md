# TIC-TAC-TOE

Let's create a simple tic tac toe game in JavaScript.

_I used HTML to create the game board,
CSS to create the game board's style, and use JavaScript to control the game._

`❌❌❌ 
⭕⭕⭕`

Tic Tac Toe is a simple well known game. It is played by two players on a 3x3 grid.

Players get their own symbol, either X or O. They have to fill in a square with their symbol on the grid when it's their turn.

The goal of the game is to get three in a row. The first player to get three in a row wins.

## Let’s break down the user interface:

-- 3x3 grid
-- the grid should be clickable
-- the grid cells should have the correct player sign displayed an information display
should display a message informing the current player it’s their turn
should show us who won the game
should show us if the game ended in a draw
restart button
will restart the entire game

### For a quick look here is our tic tac toe game:

![Screenshot 2022-06-24 182433](https://user-images.githubusercontent.com/89247662/175540202-42d32d54-2578-4db7-b763-1b7f3e362736.png)


### JavaScript Code For Tic Tac Toe
To start with writing logic for the game first take an overview of what we are going to do.

> Select all the necessary elements from the DOM. For example, cells, result, and turn counter.

> Set 'X' and 'O' as the first player and second player. Also, create an array named board to store the values of the cells.

> Start the game and attach an onclick event to each cell.

>Onclick cells will call a function that will assign the value to the cell, change the turn, store the value in the array board and check if the player won or not.

>If the player won then show the result and disable all the cells.

## Image after winning
![Screenshot 2022-06-24 182605](https://user-images.githubusercontent.com/89247662/175540470-d9cd5b4c-a831-40d9-965d-07d6a702a06f.png)

