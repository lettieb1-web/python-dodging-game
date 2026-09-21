# Python Dodging Game

A console-based interactive game developed in Python where the player moves left and right to avoid randomly generated falling obstacles. The game tracks the player's score and remaining lives and continues until all three lives are lost.

## Features

- Interactive left and right player movement
- Randomly generated falling obstacles
- Collision detection
- Three-life system
- Real-time score tracking
- Game-over screen displaying the final score
- Console-based game interface

## Controls

| Key | Action |
|-----|--------|
| A | Move Left |
| D | Move Right |

## How the Game Works

The player begins in the center of a 20-character-wide playing area with three lives.

During each turn, the player chooses to move left or right. Obstacles are randomly generated and move downward through the playing area. If an obstacle reaches the player's position, the player loses a life.

The game continues until all three lives are lost, at which point the player's final score is displayed.

## Technologies Used

- Python
- `random` module — generates random obstacle positions and spawn events
- `time` module — controls game timing
- `os` module — clears and refreshes the console display

## Programming Concepts

This project provided experience working with:

- Functions
- While loops and for loops
- Conditional statements
- Lists
- User input
- Random number generation
- Collision detection
- Game-state management
- Console output and formatting

## Running the Game

1. Make sure Python 3 is installed.
2. Download or clone this repository.
3. Open a terminal in the project directory.
4. Run:

   python interactive_game.py

5. Use `A` and `D` to control the player and avoid the falling obstacles.

## Purpose

This project was developed to apply fundamental Python programming concepts to an interactive application. The development process involved designing the game logic, implementing player movement and randomly generated obstacles, tracking lives and score, and testing the program to ensure the different game systems worked together correctly.

## Author

**Bodhi Lettieri**  
Mechanical Engineering Student, The College of New Jersey
[interactive_game.py](https://github.com/user-attachments/files/32487068/interactive.game.py)
