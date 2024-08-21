**2048 Javascript Game**

- [DEMO LINK](https://katya-sn.github.io/2048_game/)

This is a simple implementation of the popular 2048 puzzle game using pure JavaScript and SCSS for styling. 
The goal of the game is to slide numbered tiles on a 4x4 grid to combine them into a tile with the number 2048.

**Features**
1. **Smooth Tile Movement**: 
  Tiles slide in the direction of the arrow keys (Up, Down, Left, Right), combining when two tiles with the same number touch.
2. **Dynamic Board Updates**: 
  The board updates after every valid move, adding a new tile (2 or 4) in a random empty position.
3. **Score Tracking**: 
  The score is updated based on the value of the combined tiles, and displayed in real-time.
4. **Win/Lose Conditions**: 
  The game ends when you create a 2048 tile (win) or when no moves are possible (lose).
5. **Stylish Design**: 
  The game features a clean, modern look with SCSS used to handle the styling, including dynamic classes for different tile values.

  
##Technologies Used
1. **JavaScript**: 
  Core game logic and board rendering.
2. **SCSS**: 
  Custom styles with variables and mixins to ensure a consistent and scalable design.
3. **HTML/CSS**: 
  Basic layout and styling for the game grid and interface.
4. **DOM Manipulation**: 
  Used to update the game board and score dynamically based on user input.

##How It Works
1. **Game State Management**: 
  The game state, including the board and score, is managed by the Game class. This class handles all the operations such as moving tiles, combining them, and checking the game status.
2. **Tile Movement**: 
  The game processes tile movement through methods like moveLeft(), moveRight(), moveUp(), and moveDown(). These methods slide the tiles, combine them if needed, and add a new tile if the move was successful.
3. **SCSS Styling**: 
  The design is driven by SCSS, allowing for responsive and dynamic styling of the game board, including unique styles for each tile value.
4. **Game Rendering**: 
  The game is rendered by manipulating the DOM elements corresponding to the game grid. The content and classes of each cell are updated to reflect the current state of the board.
  
##How To Play
1. Simply click - [DEMO LINK](https://katya-sn.github.io/2048_game/) to start playing the game.
2. Use the arrow keys to move the tiles. Combine tiles of the same value to reach 2048.
3. If you achieve 2048 in one tile, you win! If no moves are possible, the game is over.
