# Simple Snake Game (C++)

A classic Snake game implementation written in C++.

## Description

This is a simple and fun implementation of the classic Snake game. The player controls a snake that moves around the screen, eats food, and grows longer. The game ends when the snake collides with itself or the boundaries of the game area.

## Features

- Classic Snake gameplay mechanics
- Simple and intuitive controls
- Growing snake as you eat food
- Score tracking
- Game over detection

## Requirements

- C++ compiler (C++11 or later)
- Standard C++ libraries

## Compilation

To compile the game, use your C++ compiler:

```bash
g++ -o snake main.cpp
```

Or use any other C++ compiler of your choice:

```bash
clang++ -o snake main.cpp
```

## How to Play

1. Run the compiled executable:
   ```bash
   ./snake
   ```

2. Control the snake using keyboard keys:
   - Arrow keys or WASD to move in different directions
   - ESC or Q to quit the game

3. Eat the food to grow longer and increase your score

4. Avoid colliding with the walls and yourself

5. Try to achieve the highest score possible!

## Game Rules

- The snake starts at a fixed position on the screen
- Food appears randomly on the game board
- Each food eaten increases the snake's length by one segment
- The game ends when:
  - The snake collides with itself
  - The snake goes out of bounds
- Your score increases with each food consumed

## File Structure

- `main.cpp` - Main game implementation

## Contributing

Feel free to fork this project and submit pull requests with improvements or bug fixes.

## License

This project is open source and available for educational and personal use.

## Author

Abu-Bakar-Rakib

---

Enjoy the game! 🐍
