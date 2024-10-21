Description:
The program is a command-line implementation of the classic game Rock, Paper, Scissors. The user is prompted to select between "rock," "paper," or "scissors," and the computer randomly generates a choice. Based on both selections, the program determines and prints the winner. If the user needs help, the program provides instructions for playing the game.

Functionality:
User Input: The user can choose between "rock," "paper," or "scissors."
Computer Input: The program randomly selects its own move.
Outcome Evaluation: The game compares the choices, determines the winner based on the rules, and prints an ASCII representation of both choices, followed by a result message (win/lose/tie).
Help Menu: If the user types "Help," the rules of the game are displayed.

Architecture:
User Interaction:

input(): Gets input from the user (for both the game choice and the help option).
print(): Displays ASCII representations and game results.
Game Logic:

Random Selection: The computer randomly selects from "rock," "paper," or "scissors" using random.choice().
Decision Tree: The program compares user input with computer input using conditional statements (if/elif/else), to determine the outcome of the game.

Class: RockPaperScissorsGame

Attributes:
user_choice (stores user input)
computer_choice (stores computer input)
Methods:
get_user_choice(): Prompt the user for their choice and validate input.
get_computer_choice(): Randomly generate the computer's choice.
evaluate_winner(): Determine the winner based on the game rules.
print_ascii(choice): Display the corresponding ASCII art based on the choice.
display_help(): Show game rules if requested.
