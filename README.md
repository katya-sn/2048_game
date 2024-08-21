**2048 Javascript Game**
- [DEMO LINK]([https://<your_account>.github.io/<repo_name>/](https://katya-sn.github.io/2048_game/))

This is a simple implementation of the popular 2048 puzzle game using pure JavaScript and SCSS for styling. 
The goal of the game is to slide numbered tiles on a 4x4 grid to combine them into a tile with the number 2048.

**Features**
Smooth Tile Movement: 
  Tiles slide in the direction of the arrow keys (Up, Down, Left, Right), combining when two tiles with the same number touch.
Dynamic Board Updates: 
  The board updates after every valid move, adding a new tile (2 or 4) in a random empty position.
Score Tracking: 
  The score is updated based on the value of the combined tiles, and displayed in real-time.
Win/Lose Conditions: 
  The game ends when you create a 2048 tile (win) or when no moves are possible (lose).
Stylish Design: 
  The game features a clean, modern look with SCSS used to handle the styling, including dynamic classes for different tile values.

  
**Technologies Used**
JavaScript: 
  Core game logic and board rendering.
SCSS: 
  Custom styles with variables and mixins to ensure a consistent and scalable design.
HTML/CSS: 
  Basic layout and styling for the game grid and interface.
DOM Manipulation: 
  Used to update the game board and score dynamically based on user input.

**How It Works**
Game State Management: 
  The game state, including the board and score, is managed by the Game class. This class handles all the operations such as moving tiles, combining them, and checking the game status.
Tile Movement: 
  The game processes tile movement through methods like moveLeft(), moveRight(), moveUp(), and moveDown(). These methods slide the tiles, combine them if needed, and add a new tile if the move was successful.
SCSS Styling: 
  The design is driven by SCSS, allowing for responsive and dynamic styling of the game board, including unique styles for each tile value.
Game Rendering: 
  The game is rendered by manipulating the DOM elements corresponding to the game grid. The content and classes of each cell are updated to reflect the current state of the board.
  
**How To Play**
Simply click here to start playing the game.
Use the arrow keys to move the tiles. Combine tiles of the same value to reach 2048.
If you achieve 2048 in one tile, you win! If no moves are possible, the game is over.
