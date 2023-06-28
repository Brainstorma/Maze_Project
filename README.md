# Maze Project

This project aims to create a 3D maze game using the SDL2 library. The goal is to implement raycasting to draw the walls of the maze, allow the player to navigate through the maze, and add various features such as rotation, collision detection, textures, and more.

## Requirements

- Ubuntu 14.04 LTS
- GCC (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4
- SDL2 library
- SDL2 documentation

## Getting Started

To get started with the project, follow these instructions:

1. Clone this repository to your local machine.
```
git clone [Brainstorma](https://github.com/Brainstorma/Maze_Project/)
```

2. Ensure that SDL2 is installed on your system. If not, refer to the SDL2 documentation for installation instructions.

## Usage
On the terminal run
```
make
```

This creates the executable file `raycast` (which is currently in this GitHub repository). Then run this to start up the application.

```
./raycast
```
![Maze_game](./images/Maze_game.png)

## Features

The Maze Project implements the following features:

1. Walls: The game window displays a maze with walls rendered using raycasting. Walls are differentiated from the ground/ceiling with different colors.

2. Orientation: Walls facing north/south are displayed in a different color from walls facing east/west. This allows for easy orientation within the maze.

3. Rotation: Players can rotate the camera to change their view of the maze. This helps in exploring different areas and finding the exit.

4. Movement: Players can move within the maze using keyboard inputs. The typical WASD or arrow keys can be used for movement.

5. Collision Detection: The project includes collision detection to prevent the player from passing through walls. If a collision is detected, the player's movement is stopped or adjusted to slide along the walls.

6. Parser: A parser is implemented to read the maze map from a file. The map format is defined, and the project accepts a file path as a parameter to load the map.

7. Map Display: The game includes an option to display the entire map on the window. This shows the full layout of the maze, including the player's line of sight.

8. Textures: Textures can be added to the walls, ground, and ceiling surfaces to enhance the visual appearance of the game.

9. Multi-Tasking: Players can perform multiple actions simultaneously, such as moving in multiple directions while rotating.

10. Ground Textures: The ground and/or ceiling surfaces can have textures applied to them, providing a more immersive experience.

11. Weapons: Textures and animations for weapons can be implemented, allowing players to switch between weapons as needed.

12. Enemies: Enemies can be added to the game, with their own textures, movement logic, and interaction with the player.

13. Rain: A rain effect can be added to the game environment, which can be toggled on/off with a specific key input.

14. Extra Options: Developers can get creative and add additional features like dynamic lighting effects, shadows, or special abilities.

## Contributing

Contributions to the Maze Project are welcome! If you have any ideas, bug fixes, or enhancements, please submit a pull request or open an issue on the project repository.

## License

The Maze Project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the project as per the terms of this license.

## Acknowledgments

- The creators and contributors of the SDL2 library for providing the foundation for this project.
- Online tutorials and resources used for learning about raycasting and game development with SDL2.

Feel free to modify this README.md with any additional information specific to the project. Have fun creating the maze game!
