# 🐍 Simple Snake Game

A feature-rich implementation of the classic Snake game built with modern C++.

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Controls](#controls)
- [Project Structure](#project-structure)
- [Technical Details](#technical-details)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## 📖 Overview

This project implements the classic Snake game in C++. Players navigate a snake through a game board, consuming food to grow longer while avoiding collisions with walls and their own body. The game features real-time rendering, score tracking, and smooth gameplay mechanics.

**Ideal for:**
- Learning C++ game development fundamentals
- Understanding game loops and collision detection
- Exploring console-based graphics programming
- Educational projects and coding practice

## ✨ Features

- **Classic Gameplay** - Authentic Snake game mechanics with modern implementation
- **Real-time Rendering** - Smooth, responsive graphics updates
- **Score System** - Track your progress and compete for high scores
- **Collision Detection** - Accurate detection of wall and self-collision
- **Randomized Food Placement** - Procedurally generated food positions
- **Responsive Controls** - Smooth keyboard input handling
- **Game State Management** - Proper pause, play, and game-over states

## 📦 Prerequisites

- **Compiler**: GCC, Clang, or MSVC (C++11 or later)
- **Operating System**: Linux, macOS, or Windows
- **CMake** (optional): Version 3.10 or higher for build automation

### System Requirements

- Minimum 1 MB free disk space
- Console/terminal with Unicode support (optional, for enhanced visuals)

## 🚀 Installation

### Option 1: Using g++ (Recommended)

```bash
# Clone the repository
git clone https://github.com/Abu-Bakar-Rakib/simple-Snake-under-c-.git
cd simple-Snake-under-c-

# Compile
g++ -std=c++11 -O2 -o snake main.cpp

# Run
./snake
```

### Option 2: Using Clang

```bash
clang++ -std=c++11 -O2 -o snake main.cpp
./snake
```

### Option 3: Using CMake (if available)

```bash
mkdir build
cd build
cmake ..
make
./snake
```

## 🎮 Usage

### Running the Game

```bash
./snake
```

### Basic Workflow

1. Launch the executable
2. Use controls to navigate the snake
3. Eat food to grow and increase your score
4. Avoid obstacles to survive
5. Exit when the game ends or press Q/ESC to quit

## 🎯 Game Rules

| Rule | Description |
|------|-------------|
| **Objective** | Eat as much food as possible without colliding |
| **Growth** | Snake grows by one segment for each food consumed |
| **Boundaries** | Game area is bounded; hitting edges ends the game |
| **Self-Collision** | Hitting your own body segment ends the game |
| **Scoring** | +10 points per food item consumed |
| **Speed** | Game speed increases slightly with each food eaten |

## ⌨️ Controls

| Key | Action |
|-----|--------|
| `↑` Arrow Up / `W` | Move Up |
| `↓` Arrow Down / `S` | Move Down |
| `←` Arrow Left / `A` | Move Left |
| `→` Arrow Right / `D` | Move Right |
| `ESC` / `Q` | Quit Game |
| `P` | Pause/Resume (if implemented) |

## 📁 Project Structure

```
simple-Snake-under-c-/
├── main.cpp              # Main game implementation
├── README.md             # This file
└── LICENSE               # MIT License
```

## 🔧 Technical Details

### Architecture

The game follows a classic game loop architecture:

```
Initialize → Main Loop → Render → Update → Input Handling → Check State
```

### Key Components

- **Game Loop**: Manages frame timing and game state updates
- **Collision Detection**: Checks for wall and self-collision
- **Food Generation**: Randomly places food within game boundaries
- **Input Handler**: Processes keyboard input and updates snake direction
- **Renderer**: Displays game state in console

### Performance

- **Frame Rate**: Optimized for smooth gameplay
- **Memory Usage**: Minimal memory footprint with efficient data structures
- **Compilation**: Fast compilation with O2 optimization

## 🤝 Contributing

Contributions are welcome! To contribute to this project:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Contribution Guidelines

- Follow C++ style conventions
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation if needed

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

MIT License allows you to:
- ✅ Use for personal and commercial projects
- ✅ Modify and distribute
- ✅ Use privately
- ⚠️ Include license and copyright notice

## 👤 Author

**Abu Bakar Rakib**
- GitHub: [@Abu-Bakar-Rakib](https://github.com/Abu-Bakar-Rakib)
- Email: rakibcdp@gmail.com

## 📞 Support

If you encounter any issues or have questions:

1. Check existing [issues](https://github.com/Abu-Bakar-Rakib/simple-Snake-under-c-/issues)
2. Create a new issue with detailed description
3. Include error messages and system information

## 🎓 Educational Resources

This project demonstrates:

- **Game Development**: Basic game loop architecture
- **Data Structures**: Using vectors for snake segments
- **Algorithms**: Collision detection and pathfinding
- **C++ Features**: Object-oriented design, memory management
- **Console I/O**: Input handling and rendering

## 🚀 Future Enhancements

Potential improvements for future versions:

- [ ] Graphical UI using SDL or SFML
- [ ] High score leaderboard
- [ ] Multiple difficulty levels
- [ ] Power-up system
- [ ] Sound effects and music
- [ ] Networking for multiplayer mode
- [ ] Web-based version using WebAssembly

## 📊 Statistics

- **Language**: C++11
- **Lines of Code**: Compact and efficient
- **Compilation Time**: < 1 second
- **Binary Size**: Minimal

---

<div align="center">

**Enjoy playing! 🎮**

*If you found this project helpful, please consider giving it a ⭐*

</div>
