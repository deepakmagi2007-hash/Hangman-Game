1. Introduction:
      The Hangman Game is a simple word-guessing game developed using the Python programming language. It is a popular guessing game     in which the player tries to find a hidden word by guessing one letter at a time.
  In this game, the computer selects a random word from a predefined list of words. The selected word is displayed as underscores (_),   representing the hidden letters. The player must guess the correct letters to identify the word.
  The player gets a limited number of chances to guess the word. For every correct guess, the corresponding letter is displayed in its   correct position. For every incorrect guess, the number of remaining attempts is reduced.
 The game continues until the player successfully guesses the complete word or runs out of attempts.
2. Objectives of the Project:
   1.The main objectives of the Hangman Game are:
   2.To develop an interactive word-guessing game using Python.
   3.To improve logical thinking and problem-solving skills.
   4.To understand the use of loops and conditional statements.
   5.To implement random word selection.
   6.To learn string manipulation and list operations.
   7.To provide an entertaining and educational gaming experience.
3. Technologies Used:
  Technology             Description
Programming Language        Python
Random Module            Selects a random word
String                   Stores and processes words
List                     Stores guessed letters
While Loop               Repeats the game until it ends
If-Else                  Checks correct and incorrect guesses
Input Function           Accepts letters from the player
4. Working Principle:
   The Hangman Game works through the following steps:
Step 1: Start the Game
   The game starts by displaying a welcome message to the player.
Step 2: Select a Random Word
   The computer randomly selects a word from a predefined list using Python's random module.
Step 3: Display Hidden Word
   The selected word is displayed using underscores. Each underscore represents one letter.
For example:
   If the selected word is PYTHON, it will be displayed as:
   _ _ _ _ _ _
Step 4: Get Player Input:
   The player enters one letter at a time to guess the hidden word.
Step 5: Check the Guess
   1.If the guessed letter is correct, it is displayed in the appropriate position.
   2.If the guessed letter is incorrect, the remaining attempts are reduced.
   3.If the player enters an already guessed letter, the program can display a warning.
Step 6: Continue the Game
   The game continues until the player guesses all the letters correctly or uses all available attempts.
Step 7: Display the Result
   Finally, the program displays a winning or losing message.
5. Sample Output
 The following is an example of how the Hangman Game works.
   ================================
         WELCOME TO HANGMAN
   ================================

  Guess the hidden word!
  Word: _ _ _ _ _ _
  Remaining Attempts: 6
  Enter a letter: P
  Correct guess!
  Word: P _ _ _ _ _
  Remaining Attempts: 6
  Enter a letter: A
  Wrong guess!
  Word: P _ _ _ _ _
  Remaining Attempts: 5
  Enter a letter: Y
  Correct guess!
  Word: P Y _ _ _ _
  Remaining Attempts: 5
  Enter a letter: T
  Correct guess!
  Word: P Y T _ _ _
  Remaining Attempts: 5
  Enter a letter: H
  Correct guess!
  Word: P Y T H _ _
  Remaining Attempts: 5
  Enter a letter: O
  Correct guess!
  Word: P Y T H O _
  Remaining Attempts: 5
  Enter a letter: N
  Correct guess!
  Word: P Y T H O N
================================
       CONGRATULATIONS!
          YOU WON!
================================
The correct word is PYTHON.

6. Advantages of the Project
   1.Easy to understand and play.
   2.Improves vocabulary and spelling skills.
   3.Develops logical thinking.
   4.Helps beginners understand Python programming.
   5.Provides an interactive gaming experience.
   6.Requires only basic programming concepts.

7. Applications
    1.Educational word games.
    2.Vocabulary learning applications.
    3.English language learning.
    4.Programming practice for beginners.
    5.Brain-training games.
8. Conclusion:
    The Hangman Game is a beginner-friendly Python project that demonstrates important programming concepts such as variables, lists,     loops, conditional statements, functions, and random word selection.This project helps beginners understand how Python programs        work through an interactive gaming application. It also improves logical thinking, guessing ability, and vocabulary skills.
   Overall, the Hangman Game is a useful mini-project for learning Python programming and developing basic problem-solving skills.
