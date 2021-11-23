# REPORT


# Introduction

The miniproject is developed in C Programming Language. We will be going over how we planned on implementing a TicTacToe game using C Programming Language and Run in Visual Studio Code using Github and a as many various other tools as we could testing or deployment.

# About The Project:

1. The game has a basic interface that runs in the terminal.

2. The goals of this project are:

 a. Practice with C Programming Language using Visual Studio Code.

 b. Learn how to structure, Correct use of logic and interface files to keep code maintainable.

 c. Practice of Github and Github creating branches for the different features.
 
# Methods


* display_board

  Define a method that prints the current board representation based on the @board instance variable.

* input_to_index

  Define a method into which we can pass user input (in the form of a string, e.g., "1", "5", etc.) and have it return to us the corresponding index of the @board array. Remember that, from the player's point of view, the board contains spaces 1-9. But the indices in an array start their count at 0. If the user inputs 5, your method must correctly translate that from the player's perspective to the array's perspective — accounting for the fact that @board[5] is not where the user intended to place their token.

* move

  Your #move method must take in two arguments: the index in the @board array that the player chooses and the player's token (either "X" or "O"). The second argument, the player's token, should default to "X".

* position_taken?

  The position_taken? method will be responsible for evaluating the user's desired move against the Tic Tac Toe board and checking to see whether or not that position is already occupied. Note that this method will be running after #input_to_index, so it will be checking index values. When it is passed the index value for a prospective move, #position_taken? will check to see if that position on the @board is vacant or if it contains an "X" or an "O". If the position is free, the method should return false (i.e., "the position is not taken"); otherwise, it will return true.

* valid_move?

  Build a method valid_move? that accepts a position to check and returns true if the move is valid and false or nil if not. A valid move means that the submitted position is.

* Present on the game board.

  Not already filled with a token.

* turn_count

  This method returns the number of turns that have been played based on the @board variable.

* current_player

  The #current_player method should use the #turn_count method to determine if it is "X"'s or "O"'s turn.

* turn

  Build a method #turn to encapsulate the logic of a single complete turn composed of the following routine.

Ask the user for their move by specifying a position between 1-9.
Receive the user's input.

1. Translate that input into an index value.
2. If the move is valid, make the move and display the board.
3. If the move is invalid, ask for a new move until a valid move is received.


# SWOT ANALYSIS:-

 SWOT Analysis is a simple tool that can help you to analyze what your company does best right now, and to devise a successful strategy for the future. SWOT can also reveal areas of the business that are holding you back, or that your competitors could exploit if you don't protect yourself.

 a) Strengths:

    Tic Tac Toe is in itself a wonderful game for developing planning skills as children need to plan out how they can build their own line of 4 while also watching out for what their opponent is doing so they can block their opponent from winning

 b) Weaknesses:

    Weaknesses, like strengths, are inherent features of your projects, so focus on your people, resources, systems, and procedures.

 c) Opportunity:

    They usually arise from situations outside your organization, and require an eye to what might happen in the future.

 d) Threats:

   The theft of intellectual property is one of the primary concerns for online gaming companies.

        1.Data Breaches.

        2.Ransomware and IABs.

        3.Phishing and Stolen Accounts.

# 4W's and 1'H :-

 * What:

   This helps user to increasing to more players and no monthly subscription.

 * Where:

   It has to be used easily by the users.

 * When:

   It has to be deployed 20th of November 2021.

 * Why:

   I am Developing this basic C Programming Language to perform in Visual studio code in best easy manner and improve my coding skills.

 * How:

   I am using C programming language for Developing this simple basic TiC Tac Toe Game.



# Cost and Features and Timeline :-

Cost:

No cost - Free download

5 years Ago:

Higher dimensional variations are possible.



# Detail requirements :-

* High Level Requirements



![Capture 1](https://user-images.githubusercontent.com/94240954/142771622-e7b47642-9dba-4797-9842-4fa2a0d40459.JPG)



* Low Level Requirements



![Capture 3](https://user-images.githubusercontent.com/94240954/142771671-77a75b2a-04aa-4aef-8239-dbc78ba7b6a6.JPG)


# DESIGN:-


* Structural Diagram:




![Capture pr](https://user-images.githubusercontent.com/94240954/143013940-509395bd-f944-4e79-9b2d-2690719c0dc1.JPG)


* ACTIVITY DIAGRAM:

![Capture](https://user-images.githubusercontent.com/94240954/142768455-a87c8b1e-0356-4381-a405-d5dfda8e15d7.JPG)


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




