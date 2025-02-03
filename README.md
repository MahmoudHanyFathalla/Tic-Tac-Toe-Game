# Tic Tac Toe Game

## Overview
This is a Python implementation of the classic **Tic Tac Toe** game. It allows two players to take turns placing their marks (X or O) on a 3x3 grid, aiming to get three in a row.

## Features
- Two-player gameplay (X vs. O)
- Interactive text-based interface
- Automatically detects wins and draws
- Scoreboard tracking for multiple games
- Customizable player names

## How to Play
1. Run the script.
2. Players choose whether they want to be X or O.
3. Players take turns selecting a position (1-9) to place their mark.
4. The game checks for a winner after every move.
5. The first player to align three marks in a row, column, or diagonal wins.
6. The game can be played multiple times, with scores tracked.

## Installation
No external dependencies are required. Simply run the script with Python:

```sh
python tic_tac_toe.py
```

## Code Structure
- `print_tic_tac_toe(values)`: Prints the Tic Tac Toe board.
- `print_scoreboard(score_board)`: Displays the game scoreboard.
- `check_win(player_pos, cur_player)`: Checks if a player has won.
- `check_draw(player_pos)`: Determines if the game is a draw.
- `single_game(cur_player)`: Runs a single game session.

## Example Gameplay
```
     |     |
  X  |  O  |  X
_____|_____|_____
     |     |
  O  |  X  |  O
_____|_____|_____
     |     |
  X  |  O  |  X
     |     |
Player X has won the game!!
```

## Customization
You can modify the game to change the board size or adjust other rules by editing the `single_game` function.

## License
This project is licensed under the MIT License.

