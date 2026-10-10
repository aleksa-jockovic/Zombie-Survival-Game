# Zombie Survival Game

A 2D zombie survival shooter developed independently in C++ using SFML.

The game was originally created in 2021 as a high school programming project. It features player movement, shooting mechanics, enemy tracking, and progressively increasing difficulty.

## Features

- Player movement using WASD controls
- Mouse-based aiming and shooting
- Zombies that follow the player using vector calculations
- Random enemy spawning along the screen edges
- Collision detection between bullets, zombies, and the player
- Progressive difficulty through increasing enemy speed and spawn frequency
- Game over when a zombie reaches the player

## Technologies

- C++
- SFML 2.6.2
- C++ Standard Library (std::vector)

## Controls

| Input | Action |
|---|---|
| W, A, S, D | Move |
| Mouse | Aim |
| Left Mouse Button | Shoot |

## How to Run

1. Download SFML 2.6.2 from the official website.
2. Open the C++ project in Visual Studio.
3. Configure the SFML include and library directories.
4. Link the required SFML graphics, window, and system libraries.
5. Build and run the application.

## Additional Information

The original game used external image textures. These were later replaced with SFML geometric shapes to allow the game to run without external graphical assets while preserving its original mechanics.
