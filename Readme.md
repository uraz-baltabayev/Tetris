# Tetris Game

A classic Tetris implementation using C++ and Raylib.

## Project Structure
Tetris/
├── CMakeLists.txt # Build configuration
├── main.cpp # Main game loop
├── game.cpp # Game logic implementation
├── game.h # Game class header
├── grid.cpp # Grid management
├── grid.h # Grid class header
├── block.cpp # Block base class
├── block.h # Block class header
├── blocks.cpp # Tetromino shapes
├── blocks.h # Shapes header
├── colors.cpp # Color definitions
├── colors.h # Colors header
├── position.cpp # Position class
├── position.h # Position header
├── README.md # This documentation
├── LICENSE # License file
├── Sounds/ # Audio assets
│ ├── music.mp3
│ ├── rotate.mp3
│ └── clear.mp3
├── Font/ # Font assets
│ └── monogram.ttf
└── build/ # Build directory (generated)



## Prerequisites

- CMake (version 3.10 or higher)
- Raylib library
- C++ compiler (GCC, Clang, or MSVC)

## Installation

### Install Raylib

#### macOS:
```bash
brew install raylib

Ubuntu/Debian:

bash
sudo apt install libraylib-dev

# 1. compile a game:

mkdir build
cd build

# 2. Regenerate CMake files
cmake ..

# 3. Rebuild from scratch
make clean
make
# 4. Start a game
./Tetris

