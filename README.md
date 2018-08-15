# Checkers

This is a vanilla javascript checkers game. The catch with this game is it is made with no underlying data. It gets locations and types of pieces from the html directly for each move. The system does not enforce any rules except for standard diagonal moves and jump chaining, since the only data being stored is the selected token to move. 

The fun part of this was making the jump chaining algorithm. By selecting the current piece and where to go, the game executes a recursive route finding algorithm to determine the path and move if valid.

It can support a range of board sizes, prompted at the load of the page.

Languages: HTML, CSS, JS
