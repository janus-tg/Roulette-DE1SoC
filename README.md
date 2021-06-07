# Roulette-DE1SoC
A C program to play roulette for the DE1SoC board that lets the user input a number via the PS/2 keyboard. Then, the result of the roulette wheel, the user input, total wins/losses and the winnings are displayed on the VGA pixel buffer.

## Background

A fixed amount of $10 is bet for each round of the game. The user enters a digit from 0-9 on the PS/2 keyboard of the Altera DE1-SoC board. This number is passed to a random number generator written in C that returns a single digit number. If the user's input and the number gerated randomly matches, then the user has won or else they have lost. The number of wins, losses, the user input and the 
