# chain-reaction-game
The game can be played between 2 to 8 players.
The gameplay takes place on a 9*6 grid. Each cell has a specific critical mass defined. Each player takes turn to place an orb in the grid cells. Orbs get stacked up in cells until they exceed critical mass which triggers chain-reaction
The core functionality of the game i.e. chain-reaction is implemented using the Graph-Algorithm: Breadth-First-Search(BFS).
When the player taps on any block, the first function call executes to change function. This function calls other functions like updateBlock, bfs, checkForWin, changePlayerTurn etc. As the function name suggests, this takes care of all tasks like updating table, performing chain-reaction, checking for winning, changing player turn
Used asynchronous javascript, dom manipulation
