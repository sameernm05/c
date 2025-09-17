This is a simple Tic Tac Toe (XO) game implemented in C language, playable in the terminal.
It supports two players (Player A and Player B) and uses a 3x3 grid.





📌 Features

Two-player gameplay (Player A = *, Player B = o)

Players take turns to mark their positions on a 3x3 grid

Input validation – prevents overwriting already filled cells

Declares the winner if any player completes:

A row

A column

A diagonal

Declares Game Over if no winner after 9 moves

Colorful terminal text effects using ANSI escape codes






🎯 Gameplay Instructions

1)The grid is numbered from 1 to 9 as shown below:
- - -            1 2 3
- - -            4 5 6
- - -            7 8 9

2)Player A (*) always starts first.

3)Enter a number between 1–9 to mark your move.

4)If the chosen cell is already filled, you will be asked to re-enter.

5)The game ends when:
A player wins (three in a row, column, or diagonal)

6)All 9 cells are filled (draw → "game over")



🖼️ Example Gameplay
- - -            1 2 3
- - -            4 5 6
- - -            7 8 9

 GAME BEGIN 

enter player 'A' data
5

- - -            1 2 3
- * -            4 5 6
- - -            7 8 9


🚀 Future Improvements

Add single-player mode (with basic AI).

Better UI (grid borders).

Replay option after game ends.

