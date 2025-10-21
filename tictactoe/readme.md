## Features

- Full Tic Tac Toe game logic:
  - `player(board)` – returns the player whose turn it is (`X` or `O`).
  - `actions(board)` – returns all possible moves on the board.
  - `result(board, action)` – returns the board after a move.
  - `winner(board)` – determines the winner if there is one.
  - `terminal(board)` – checks if the game is over (win or tie).
  - `utility(board)` – evaluates the board (+1 for X win, -1 for O win, 0 for tie).
- **Minimax AI**:
  - Computes the optimal move for the current player.
  - Always chooses moves to **win or block opponent**.
- Fully compatible with the provided `runner.py`.
