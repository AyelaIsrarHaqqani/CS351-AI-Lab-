# Snake Game in Python

This is a simple console-based Snake Game implemented in Python. 
The game uses a grid where the snake moves around to eat food, avoiding walls and its own body.
As the snake eats the food, it grows in length, making the game progressively harder.

# Features

- Playable on a grid of any size (default: 10x10).
- Snake grows after eating food.
- Game over when the snake hits the wall or itself.
- Simple `W`, `A`, `S`, `D` controls to move the snake up, down, left, and right.
- The grid and snake are displayed with clear borders for easy visibility.

## How to Play

1. **Start the game**: 
   - Run the Python script in your terminal.
   - Enter the desired grid size (e.g., 10 for a 10x10 grid).
   
2. **Control the snake**:
   - Use the following keys to control the snake:
     - `W` to move **up**
     - `A` to move **left**
     - `S` to move **down**
     - `D` to move **right**

3. **Objective**:
   - Guide the snake to eat the food (represented by `F`).
   - Avoid hitting the walls or the snake's own body.
   - The game will end if you collide with the wall or the snake itself.

## Prerequisites

- Python 3.x
- The `os`, `random`, and `time` modules (these are included in the Python standard library, so no additional installations are required).


