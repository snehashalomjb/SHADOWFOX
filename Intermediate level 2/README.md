Hangman Game in Python using Turtle library

Description:
  This Python program is a simple Hangman game implemented using the Turtle graphics library. 
  The game allows players to guess a randomly selected word from a list and provides hints to help them guess the word 
  correctly. Players can input their guesses via a dialog box and see the progress of their guesses displayed on the screen.

File Structure:
  hangman.py: The main Python script containing the Hangman game logic.
  words.txt: A text file containing a list of words along with corresponding hints. 
             Each word and hint pair is separated by a colon (:).

How to Play:
  Run the hangman.py script.
  The game will display a blank Hangman drawing along with underscores representing each letter of the word to guess.
  Players can input their guesses via the dialog box that appears, along with a hint to help them guess the word.
  If the player guesses a correct letter, it will be revealed in the word. If the guess is incorrect, a part of the Hangman
    drawing will be drawn.
  The game continues until the player guesses the word correctly or makes six incorrect guesses.
  After each game, players have the option to play again or exit the game.

Additional Notes:
  The Hangman drawing is created using the Turtle graphics library.
  The words and hints used in the game are stored in the words.txt file.
  Players are provided with a hint to help them guess the word correctly.
  The game ends when the player guesses the word correctly or makes six incorrect guesses.
