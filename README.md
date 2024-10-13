                                              Guessing Game

  Overview
  
This program is a simple guessing game where the user has to guess a randomly generated number. The program provides feedback if the guess is too high or too low and continues until the user correctly guesses the number. It then displays the number of attempts it took to win the game.

Features
Generates a random number

Prompts the user to input their guess

Provides feedback if the guess is too high or too low

Displays the number of attempts after correctly guessing the number

How to Use
Start the Game: Run the program to start the game.

Input Guess: Enter your guess when prompted.

Receive Feedback: The program will tell you if your guess is too high or too low.

Repeat: Continue guessing until you guess the correct number.

Attempts Count: The program will display the number of attempts it took to guess the correct number.

Example
If the generated number is 42:

User guesses 30: "Too low, try again."

User guesses 50: "Too high, try again."

User guesses 42: "Congratulations! You've guessed the number in 3 attempts."

Requirements
C Compiler (e.g., GCC)

Standard C Library

Compilation
To compile the program, use the following command:

code:-
gcc -o guessing_game guessing_game.c

Execution
To run the program, use the following command:

code:-
./guessing_game
