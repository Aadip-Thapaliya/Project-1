# Project-1
This is a classic Tic Tac Toe (or Noughts and Crosses) game implemented in Python for two players. The game is played in the terminal/console with an interactive prompt guiding the players through the gameplay.
 Features:
Two-player mode (Player 1 and Player 2)

Turn-based play with random selection of who goes first

Custom markers (X or O) chosen by Player 1

Board is reset after each game

Detects win, draw, or ongoing game states

Option to replay after a game ends


 How It Works:
The board is represented as a list of 10 strings (index 0 is ignored for easier mapping from user input to positions).

Players are prompted to choose their markers.

The game randomly selects which player goes first.

Players take turns placing their markers on the board by selecting positions (1–9).

After each move, the game checks for a win or draw.

The game continues until a player wins, the board is full (draw), or players choose not to replay.

🛠️ Dependencies:
Only Python standard library is used

No external packages needed

📌 Example Board Position Mapping:
  7  |  8  |  9
-----|-----|-----
  4  |  5  |  6
-----|-----|-----
  1  |  2  |  3


