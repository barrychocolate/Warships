# Warships
The is a python coding challenge for the one-player game of WARSHIPS.  

## Aim of the game
The aim of the game is to destroy all the ships that are hidden in a  10×10  grid called the "Board".

## Program summary
Before the start of the game, computer places five ships on the Board. The player is not told where the ships are placed. Each ship occupies a number of consecutive squares on the board determined by the type of ship that it is:

* Each square will either be occupied by the character '-' or by first letter in the ship name.
* The ships can only be placed horizontally to the right or vertically downwards on the board as shown in the figure above and cannot be placed diagonally.
* The player fires a shot by specifying the location of a square on the board.
* To specify the location of a square the player enters a number for the column (between  0  and  9 ) and then a number for the row(between  0  and  9 ).
* If the shot fired hits a ship it is called a 'hit' and the letter 'h' is used to show this on the board, otherwise it is called a 'miss' and the letter 'm' is used to show this on the board.
* A ship is destroyed when all the squares that it occupies have been ‘hit’.
* The player wins the game when all the ships have been destroyed.

You are required to write a collection of functions to carry out all the tasks in the game.

Your functions and the code need to be commented throughout using docstrings and comments in Python.
