cmake_minimum_required(VERSION 3.16)
project(Tetris)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Homebrew Raylib path

set(RAYLIB_HOME /opt/homebrew)

include_directories(${RAYLIB_HOME}/include)
link_directories(${RAYLIB_HOME}/lib)

add_executable(Tetris
main.cpp
grid.cpp
colors.cpp
block.cpp
blocks.cpp
position.cpp
game.cpp
)

target_link_libraries(Tetris
raylib
"-framework OpenGL"
"-framework Cocoa"
"-framework IOKit"
"-framework CoreVideo"
)
# Extend the clean target to also remove .o and .d files
set_directory_properties(PROPERTIES ADDITIONAL_CLEAN_FILES "*.o;*.d")

