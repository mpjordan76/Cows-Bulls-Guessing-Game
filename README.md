# Cows-Bulls-Guessing-Game
This is a game I made for practice while learning Python. It was a challenge from practicepython.org.

If you're not familiar with the game of "Cows & Bulls", the player simply has to guess a secret, 4-digit number. In their guess, if a digit is the right number AND in the right position, the player gets a 'cow'. If the digit is present in the secret number, but in the wrong position, the player gets a 'bull'. The goal is to have 4 'cows', that is, guess the secret number.

My program creates a random number between 0001 and 9999, and it allows for easy (unlimited guesses) and hard (10 guesses) modes. Furthermore, many users seemed to have trouble when the randomly generated secret number had repeated digits (such as 2020, 1333, or 7777). Their programs would print incorrect counts for bulls. I, too, expreienced this, but I'm proud that I figured out a way to remedy this issue. I explain how within the source code.

Any tips/advice on how to make my code better, more readable, or simpler are welcomed!
