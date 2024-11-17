# Rock, Paper, Scissors Game

A simple **Rock, Paper, Scissors** game where you play against the computer! The game runs in the terminal and uses emojis to represent each choice.


## Features:
- User chooses between Rock (🪨), Paper (📜), or Scissors (✂️).
- The computer randomly selects one of the three options.
- The game determines the winner based on standard Rock, Paper, Scissors rules:
  - Rock beats Scissors
  - Scissors beats Paper
  - Paper beats Rock
- The game continues until the user decides to quit.


## Game Flow:
1. The user is prompted to input their choice (Rock, Paper, or Scissors) using the keys `r`, `p`, or `s`.
2. If the user provides an invalid input, they are asked to choose again.
3. The computer randomly selects a choice.
4. The winner is determined based on the rules, and the result is displayed along with both the user's and the computer's choices (using emojis).
5. After each round, the user is asked if they want to play again. If they type `n`, the game ends with a thank-you message.


## How to Play:
1. Clone or download the repository.
2. Run the Python script `rock_paper_scissors.py` in your terminal or command prompt.
3. Follow the prompts:
   - Enter `r` for Rock 🪨
   - Enter `p` for Paper 📜
   - Enter `s` for Scissors ✂️
4. The game will display the result of the round, and you will be asked if you want to continue.
5. Type `y` to play another round, or `n` to exit.


## Requirements:
- Python 3.x
- No additional libraries required.


## Example Gameplay:

```bash
Rock, Paper, or scissors? (r/p/s): r
You chose 🪨
Computer chose 📜
You Win!

Continue? (y/n): y
Rock, Paper, or scissors? (r/p/s): s
You chose ✂️
Computer chose 🪨
You Lose!!!!!

Continue? (y/n): n
Have a lovely day!
```


## Code Structure:

- get_user_choice() - Prompts the user for their choice and handles invalid inputs.
- display_choices() - Displays the choices made by both the user and the computer.
- determine_winner() - Determines the winner of the round based on the rules.
- play_game() - Controls the main flow of the game, allowing the user to play multiple rounds.


## License:

This project is open source and available under the Apache License.


## Author:

Name: Mischa Doctor
GitHub: docmischa990

