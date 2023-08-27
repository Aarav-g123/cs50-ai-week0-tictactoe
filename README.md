# Tic-Tac-Toe AI using Minimax Algorithm

This project implements an AI player for Tic-Tac-Toe that plays optimally using the Minimax algorithm. The project consists of two main files: `runner.py` and `tictactoe.py`. The game logic and optimal move calculations are contained in `tictactoe.py`, while `runner.py` provides the graphical interface to play the game.

## Files

### tictactoe.py

This file contains the logic for playing the Tic-Tac-Toe game and making optimal moves using the Minimax algorithm. The key functions and components in this file include:

- `initial_state()`: This function returns the starting state of the Tic-Tac-Toe board. The board is represented as a list of three lists, each containing three values - 'X', 'O', or 'EMPTY'.

- `actions(state)`: Given a state of the board, this function returns a list of possible actions that can be taken.

- `result(state, action)`: Given a state and an action, this function returns the resulting state after applying the action on the board.

- `winner(state)`: This function determines if a player has won the game and returns the winner ('X', 'O', or None).

- `terminal(state)`: Checks if the game has ended in a win, loss, or draw.

- `minimax(state)`: Implements the Minimax algorithm to determine the optimal move for the AI player.

### runner.py

This file contains the code to run the graphical interface for the Tic-Tac-Toe game. It utilizes the `pygame` library to provide a visual representation of the game board and interactions.

## Getting Started

1. Once in the project directory, install the required Python package using the following command:

```bash
pip3 install -r requirements.txt
```

2. To start the game interface, run the following command:

```bash
python3 runner.py
```

3. Play the Tic-Tac-Toe game against the AI player. The AI will make optimal moves using the Minimax algorithm.

## License

This project is provided under the MIT license.

## Credits

This project is a part of CS50 AI Week 0 Tic-Tac-Toe project, offered by Harvard's CS course on edX. The AI implementation is based on the Minimax algorithm.

For any questions or issues related to the code, feel free to contact me.

Enjoy playing Tic-Tac-Toe against the AI!
