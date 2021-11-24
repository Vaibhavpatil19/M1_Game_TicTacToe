# DESIGN:-

To begin with we had figure out the basic logic of the game and how we were going to implement that. The following list describe the core elements we needed to implement.

* The board:

   A 3x3 square stored in a two dimensional array

* Players:

  1. Two players, O and X
  2. Array to keep track of score
  3. Players can be both X or O, depending on game
  4. Player makes a move
  5. 5Take a command from keyboard/mouse and change the board array
  6. Check if that move is valid
  7. Check if player won the game or if it’s a draw 

* The user interface

  1. Display the board
  2. Ask for input / get input
  3. Give input to controller and make the move.
