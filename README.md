###Description

The game "Virus Battle in 3025" simulates a scenario where the player, representing a doctor, is shrunk down to the size of bacteria to fight off viruses within the human body. The player must solve mathematical equations to damage viruses in three stages, each representing a different type of virus. The player starts with three lives, and each incorrect answer results in losing one life. The game combines educational elements (solving math problems) with entertainment through a themed narrative.

###Functionality
This program has several key functionalities:

Welcome Message: Displays a welcome message with game details.
Virus Representation: Each virus has a unique ASCII art representation.
Mathematical Challenges: The player must solve:
First-degree equations in the first two stages.
Second-degree equations in the final stage.
Health System: Each virus has health points, and the player must reduce the virus's health to zero to win that stage.
Life System: The player starts with three lives, which are lost upon incorrect answers.
Game End Conditions: The game concludes when either all viruses are defeated or the player loses all their lives.
Input Validation: The program handles invalid inputs gracefully by reducing a life and continuing the game.

###Architecture
The architecture of the game can be described in terms of its main components (functions and attributes). While the provided code does not use classes, I will outline how it could be organized if classes were to be implemented.

Classes and Methods
Game Class: This could encapsulate the overall game logic.
Attributes:
doctor_lives: Integer representing the number of lives the player has.
viruses: List of virus objects, each containing health points and ASCII art.

###Methods
__init__(): Initializes the game state (lives, virus states).

display_welcome_message(): Shows the welcome message and game instructions.

play_stage(virus): Handles the gameplay for a given virus, including equation generation and checking answers.

generate_first_degree_equation(): Generates a random first-degree equation and returns its answer.

generate_second_degree_equation(): Generates a random second-degree equation and returns its answer and possible roots.

check_answer(): Validates the player's answer and updates health/lives accordingly.

game_over(): Displays the end game message based on the outcome.
