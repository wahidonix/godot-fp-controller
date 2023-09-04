# Godot First-Person Controller README

## Overview

This is a simple first-person controller script for the Godot game engine. It provides basic motion controls for your player character, including running, jumping, crouching, sliding, and rolling when falling from a great height. This README will guide you through setting up and using the controller in your Godot project.

![Demo](link_to_demo_gif_or_image)

## Features

- First-person perspective for player control.
- Smooth camera movement.
- Basic motion controls: walking, running, jumping, and crouching.
- Sliding and rolling when falling from a great height for added realism.
- Customizable parameters to tweak movement behavior to your liking.

## Getting Started

### Prerequisites

Before using this script, make sure you have the following:

- [Godot Engine](https://godotengine.org/download) installed on your computer.
- A basic understanding of Godot and GDScript.

### Installation

1. Clone or download the repository to your local machine.
2. Open your Godot project or create a new one if you don't have one already.
3. Add the `first_person_controller.gd` script to your player character node.

### Usage

1. Attach the `first_person_controller.gd` script to your player character node.

2. Configure the parameters in the inspector to match your game's needs. Here are some important variables you can customize:

   - **Movement Speed:** Adjust the walking and running speeds.
   - **Jump Height:** Set the jump height for your player character.
   - **Crouch Height:** Define the height the player crouches to.
   - **Slide Angle:** Specify the angle at which the player should start sliding when falling.
   - **Roll Angle:** Determine the angle at which the player should perform a roll when falling from a great height.
   - **Gravity:** Customize the strength of gravity affecting the player.

3. You can also add a camera node as a child of your player character node for a smooth first-person perspective. Ensure the camera is correctly positioned and oriented.

4. Playtest your game and enjoy your first-person controller with basic motions!

## Controls

- **W, A, S, D** or arrow keys: Move forward, left, backward, and right.
- **Spacebar**: Jump.
- **Left Shift**: Hold to run.
- **Left Ctrl**: Hold to crouch.
- **Mouse Movement**: Look around.

## Contributing

Contributions and improvements are welcome! Feel free to fork this repository, make changes, and submit pull requests.

If you encounter any issues or have suggestions for improvements, please [open an issue](https://github.com/your-repository/issues).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to the Godot community for their support and inspiration.
- Inspired by various first-person controller implementations in Godot.

Thank you for using the Godot First-Person Controller! Happy game development!
