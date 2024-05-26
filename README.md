Key Components
Random Number Generation:

A list of 4 unique digits is generated randomly from a predefined set of numbers (1 to 6).
This list represents the target number the player needs to guess.
Player Interaction:

The player is prompted to enter their name, which is then used to personalize the welcome message.
The player is informed about the color mapping of the digits.
The game tracks the player's attempts and provides feedback on each guess.
Game Loop:

The player has up to 8 attempts to guess the 4-digit number.
For each attempt, the player inputs a 4-digit number.
The input is validated to ensure all digits are within the range of 1 to 6.
The game compares the player's guess to the target number and provides feedback.
Feedback Mechanism:

The feedback indicates how many digits are correct and in the correct position (represented by '1') and how many digits are correct but in the wrong position (represented by '0').
The feedback is displayed in a specific format after each guess.
Scoring:

The player's score is calculated based on the number of attempts taken to guess the number correctly.
The score starts at 100 points and decreases by 12.5 points for each incorrect attempt.
Replay Option:

After each game, the player is asked if they want to play again.
If the player chooses to play again, the game restarts with a new random number.
