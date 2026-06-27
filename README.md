# hangman_game
Hangman Game

Project Description

This is a simple command-line Hangman game developed in Python. The program randomly selects a fruit name from a predefined list, and the player must guess the word one letter at a time before running out of attempts.

Features

- Randomly selects a word from a predefined list.
- Displays a hint ("Fruit Name").
- Allows the user to guess one letter at a time.
- Tracks correct and incorrect guesses.
- Prevents duplicate letter entries.
- Validates user input.
- Ends the game with a win or loss message.

Technologies Used

- Python 3
- Random Module
- Lists
- Loops
- Conditional Statements
- User Input

How to Run

1. Make sure Python 3 is installed.
2. Save the program as "hangman.py".
3. Open a terminal or command prompt.
4. Run the program using:

python hangman.py

5. Follow the on-screen instructions to guess the word.

Game Rules

- The hidden word is the name of a fruit.
- Guess one letter at a time.
- You have a maximum of 6 incorrect guesses.
- Enter only one alphabetic character at a time.
- Guess all the letters correctly before your attempts run out to win the game.

Sample Output

Welcome to the Hangman game!
Hint = Fruit Name

Word: _ _ _ _ _
Incorrect guesses left: 6

Enter a letter: a
Correct guess!

Word: a _ _ _ e
Incorrect guesses left: 6

Project Structure

hangman.py      # Main Python program
README.md       # Project documentation

Future Improvements

- Add multiple categories (animals, countries, movies, etc.).
- Display ASCII Hangman graphics.
- Allow players to choose difficulty levels.
- Add score tracking and multiple rounds.

Author

Kiran
