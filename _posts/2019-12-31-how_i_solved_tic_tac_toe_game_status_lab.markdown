---
layout: post
title:      "How I Solved Tic Tac Toe Game Status Lab"
date:       2019-12-31 06:47:38 +0000
permalink:  how_i_solved_tic_tac_toe_game_status_lab
---


The first thing I do when I try to solve any lab is read the entire README to get a general idea of what is required to solve it. Reading through the README, the lab wants you to build helper methods (methods that you use in other methods) to inform you on different states of the game. For example, the #winner method lets you know if the person using the token  "X" has won the game, it returns "X" and if the person using "O" has won the game, it returns "O."

The first thing I did was define the constant variable WIN_COMBINATIONS for a game of tic tac toe. It is important to define a what a win combination is so there can be so I can define the #won? method. I did this by using a nested array.

Next I built a method to check the status if one of the players #won? or not.  I did this by using the each iteration over a nested array (WIN_COMBINATIONS).

Next I needed to make sure the code could evaluate if the board was #full? or not. I did this usng the all? iteration. 

After that step I needed to make sure the game could recognize that the board was at a #draw?. I did this by using having the game recognize a draw as not a win and a full board. This was done by using the && boolean operator.

Next I needed the program to check if the game was #over? by recognizing if the board was #full or the game is #won?.  I did this by using the || boolean operator.

The last step I needed to complete my lab for a tic tac toe game was #winner was and by present the winning player's token. I did this by using the if statement to check and return the wining player's token.  
