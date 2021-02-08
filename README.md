# 2048 Game
2048 is a single-player sliding tile puzzle video game.The objective of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.
In this game, you are expected to implement the move function for this game. Arguments passed to the four functions is the matrix which we are using for 2048. The move function will be returning new matrix after moving the corresponding move.
Implement All The Four Moves Using These Functions -
1. move_up
2. move_down
3. move_left
4. move_right

Go to main file i.e 2048.py
In cmd add the directory folder and then run this python file.
eg-c\users\xyzname>python 2048.py
The UI will look like 4X4 grid

How to play the game ?
The rules are also simple.2048 is played on a plain 4×4 grid, with numbered tiles that slide when a player moves them using the four keys that are  w,s,a,d for key_up, key_down, key_left, key_right respectively. Every turn, a new tile randomly appears in an empty spot on the board with a value of 2.Tiles slide as far as possible in the choosen direction until they are stopped by either another tile or the edge of the grid. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided. The resulting tile cannot merge with another tile again in the same move. The game is won when a tile with a value of 2048 appears on the board, hence the name of the game. After reaching  the 2048 tile, players can continue to play (beyond the 2048 tile) to reach higher scores. When the player has no legal moves (there are no empty spaces and no adjacent tiles with the same value), the game ends

Note:Works well in windows or Python 3
For MAC please go to 2048.py and change "tkinter" to "Tkinter" or Python 2 and enjoy!
eg-c\users\xyzname>python2 2048.py

