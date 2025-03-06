# Snake Xenia Game

**Snake Xenia** is a simple snake game built using Python and the Pygame library. In this game, the player controls a snake that moves around the screen and eats food. Each time the snake eats food, it grows in size, and the player's score increases. The game ends when the snake collides with itself or the screen boundaries.

## Requirements

- Python 3.x
- Pygame library

To install Pygame, run the following command:
```bash
pip install pygame
```

## How to Play

1. **Start the Game**: 
   - Run the script using Python:
     ```bash
     python snake_game.py
     ```
   - On the main menu, press `1` to start the game.

2. **Controls**: 
   - Use the arrow keys to control the snake's movement:
     - Left Arrow (`←`): Move left
     - Right Arrow (`→`): Move right
     - Up Arrow (`↑`): Move up
     - Down Arrow (`↓`): Move down

3. **Objective**: 
   - Eat the food (red square) to grow the snake and increase your score.
   - Avoid colliding with the snake's own body or the screen boundaries.

4. **Game Over**:
   - The game ends if the snake collides with itself or the boundaries.
   - The score will be displayed, and the game will give an option to restart or quit.

5. **High Score**:
   - The high score will be displayed at the top of the screen. It is saved across sessions and will update if you beat the previous high score.

## Game Structure

- **Snake**: The snake is made up of segments. It moves by updating the position of the head and shifting the body. It grows when it eats food.
- **Food**: The food is a red square that randomly appears on the screen. The snake eats the food by colliding with it, which increases the snake's length and score.
- **Main Menu**: The game starts with a simple main menu. The player can choose to start the game by pressing `1` or quit by pressing `2`.

## Game Flow

1. Start at the main menu, where you can press `1` to begin the game or `2` to quit.
2. The snake moves around the screen. You control the movement with the arrow keys.
3. The game continues until the snake collides with itself or the boundaries.
4. Once the game ends, the score is displayed along with an option to either restart or quit.

## Features

- Simple and easy-to-understand game mechanics.
- High score tracking.
- Basic collision detection.
- User-friendly menu interface.

## License

This game is open-source and free to use. You can modify and distribute it under the terms of the MIT License.
