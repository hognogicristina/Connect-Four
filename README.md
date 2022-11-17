# Connect-Four
Connect Four is a two-player connection board game, in which the players choose a color and then take turns dropping colored tokens into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own tokens. Connect Four is a solved game. The first player can always win by playing the right moves.

**Object:** Connect four of your checkers in a row while preventing your opponent from doing the same. But, look out – your opponent can sneak up on you and win the game!

## Requirements
- Used: object oriented programming and layered architecture
- All modules with the exception of the UI are covered with specifications and PyUnit test cases
- The program is protecting itself against the user’s invalid input

**NB!**  The program is employing a strategy when making its moves in order to attempt to win the game and provide an entertaining opponent for the human player. Minimally, the computer player moves to win the game whenever possible and blocks the human player’s attempts at 1-move victory, whenever possible.

## GUI
- In addition to the console-based user interface required, I also implement a graphical user interface (GUI) for the program
- I also have both user interfaces (menu-based and graphical) use the same program layers. The project is able to start the application with either user interface
