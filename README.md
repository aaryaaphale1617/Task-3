This Python program is a fully functional Hangman game created using the Pygame library. It provides an interactive and graphical experience compared to the traditional text-based Hangman. The game is designed with the following main features:

Graphical User Interface (GUI)

Uses Pygame to create a window, display text, draw shapes, and update graphics in real time.

Displays the game title, hint for the word, score, number of incorrect guesses, and clickable letter buttons.

Word Selection and Hint System

A predefined list of words is stored with associated hints.

A random word is selected each round, and its hint is shown to guide the player.

Interactive Gameplay

Players guess letters by clicking on circular buttons representing the alphabet.

Correct guesses reveal letters in the word; incorrect guesses add a new part to the hangman drawing.

Hangman Drawing Logic

The figure is drawn step-by-step based on the number of wrong guesses.

The gallows and body parts are drawn using Pygame’s draw functions.

Win and Loss Conditions

Win: All letters are guessed before the hangman is fully drawn.

Loss: Six incorrect guesses result in the complete hangman figure being drawn.

After each round, the player can press SPACE to restart or ESC to quit.

Scoring System

The score increases with each win.

Incorrect guesses are displayed alongside the maximum allowed attempts.

Code Concepts Demonstrated

Randomization: Randomly selecting words.

Event Handling: Detecting mouse clicks and key presses.

Collision Detection: Checking if a click is inside a letter’s button.

Drawing: Using Pygame functions to render text, shapes, and the hangman figure.

Game Loop: Continuous screen updates until the game ends.

✅ Final Summary:
This Hangman game showcases Python game development skills by combining logic, user interaction, and graphics. It effectively teaches how to use Pygame for real-time drawing, handle user input events, and implement a complete game loop. With enhancements like background images, sound effects, or more words, it could become an even more engaging and polished game.


