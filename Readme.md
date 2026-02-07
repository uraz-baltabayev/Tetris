# Tetris (C++)

Welcome to **Tetris** — a classic tile‑matching puzzle game implemented in C++!  
This project recreates the iconic Tetris gameplay where players rotate and drop falling pieces (tetrominoes) to complete horizontal lines and score points.

---

## 🎮 Features

- Classic Tetris gameplay with tetromino rotation and line clearing
- Keyboard input handling
- Basic graphics rendering using built‑in or library support (e.g., SDL2/SFML/OpenGL)
- Includes **fonts** and **graphics** for in‑game visuals
- Built with **CMake** for an easy cross‑platform build

---

## 🚀 Build & Run

### 🧰 Prerequisites

- A C++ compiler (e.g., g++, clang++, or Visual Studio)
- CMake (to configure and generate build files)
- Game graphics and font libraries depending on your implementation (SDL2, SFML, etc.), if used

---

### 📋 Clone the Repo

```bash
git clone https://github.com/uraz-baltabayev/Tetris.git
cd Tetris

mkdir build
cd build
cmake ..
make

./Tetris


Tetris/
├── CMakeLists.txt
├── main.cpp
├── game.* # Game logic
├── grid.* # Grid management
├── block.* # Block base class
├── blocks.* # Tetromino shapes
├── colors.* # Color definitions
├── position.* # Position utilities
├── Font/ # Font assets
├── Sounds/ # Sound assets
└── README.md