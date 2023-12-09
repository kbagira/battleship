# battleship
Game Setup:

The game is played on an 7x7 grid.
Two ships of length 3 cells, two ships of length 2 cells, and four single-cell ships are placed randomly on the grid.
Ships cannot overlap or be placed diagonally.

Rules:

Ships are represented by the number '1' on the grid.
Empty cells are represented by '0' .
Missed shots are represented by '8'.
The game ends when all ships are sunk.


Interacting with the Game:

Upon starting the game, the initial display shows an empty grid with row and column numbers.
The computer randomly places ships on the grid, ensuring they don't overlap or violate placement rules.
The player is prompted to enter coordinates (row, col) to make a shot.
If the shot hits a ship, the display updates, and 'Hit!' is printed. If it misses, the display updates, and 'Miss!' is printed. 
The game continues until all ships are sunk. After each shot, the player needs to press Enter to continue.
