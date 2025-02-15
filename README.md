# Cub3D

Cub3D is a 3D maze game simulator. This project demonstrates the use of basic game development and graphics programming concepts by rendering a 3D map. The player navigates and interacts with the environment in a 3D world. It is developed using the C programming language and the **MLX42** graphics library.

## Contents

- **3D Maze Game**: The player navigates through a 3D world based on a 2D map.
- **Graphics Rendering**: 3D visuals are rendered using the MLX42 library.
- **Movement and Navigation**: The player can move and look around using the keyboard and mouse.

## Getting Started

Follow the instructions below to set up and run the project on your local machine.

### Requirements

- **C Compiler** (gcc or clang)
- **CMake** (for configuration and building)
- **Make** (build tool)

### Installation

Follow these steps to set up the project:

1. **Clone the Repository**:

   ```bash
   git clone --recursive https://github.com/X3l1m/cub3d.git
   cd cub3d
   ```

2. **Install Dependencies**:

   - Install the `MLX42` library and other necessary dependencies.

   ```bash
   sudo apt update
   sudo apt install build-essential libx11-dev libglfw3-dev libglfw3 xorg-dev
   ```

3. **Build the Project**:

   ```bash
   make
   ```

4. **Run the Project**:

   ```bash
   ./cub3d maps/map.cub
   ```

   The `map.cub` is the map file used in the game. You can test the game with different map files.

### Controls

- **W, A, S, D**: Move
- **Left Right Arrow**: Look around
- **Esc**: Exit the game
