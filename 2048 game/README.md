# 2048 Game - Python

This project is a Python implementation of the popular game 2048. The game is built using the Pygame library and features a graphical user interface.

## Game Overview

The game is played on a 4x4 grid, with numbered tiles that slide when a player moves them using the keyboard. The objective is to combine tiles of the same number to create a tile with the number 2048.

## Code Structure

The code is structured around several key functions and a `Tile` class:

- **Tile Class**: This class represents an individual tile in the game. Each tile has a value, a position (row and column), and a color that depends on its value. The class also includes methods for drawing the tile, moving the tile, and updating its position.

- **draw_grid()**: This function draws the grid structure of the game on the window.

- **get_random_pos()**: This function returns a random position for a new tile.

- **move_tiles()**: This function moves the tiles in a given direction and merges them if possible. It returns the updated tiles.

- **end_move()**: This function checks the end game state. If the game is over, it returns 'lost'. Otherwise, it returns 'continue'.

- **update_tiles()**: This function updates the tiles in the dictionary.

- **generate_tiles()**: This function generates the initial tiles at the start of the game.

- **main()**: This is the main function that runs the game. It initializes the game, handles events, updates the game state, and renders the game on the screen.

## Learnings from this Project

This project provided valuable experience in:

- **Game Development**: Building a game from scratch helped understand the mechanics of game development, including game loops, handling user input, and rendering graphics.

- **Object-Oriented Programming**: The use of a class to represent game elements (tiles) is a practical application of OOP principles.

- **Pygame Library**: This project offered hands-on experience with Pygame, a set of Python modules designed for writing video games.

- **Problem-Solving**: Implementing the game logic, particularly the tile merging and movement, required problem-solving and algorithmic thinking.
