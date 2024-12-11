# Battleship-bangers
 A 2D arcade rocket game made using python 
The project is a simple Python-based Space Game that involves two types of characters: the player
character and an army of enemy invaders. The game is built using the Pygame library. Here is a high-level
description of the project's components and functionality:
Basic Setup: The project starts by importing the Pygame library and setting up the game window with
specific dimensions. The window is titled "Space Shooter Tutorial."
Character and Asset Setup: Various game assets are loaded, including player characters (spaceships) and
enemy ships, as well as laser images for shooting. These assets are loaded from image files in the "assets"
folder.
Laser Class: A class for handling lasers is defined, which includes attributes such as position, image, and
collision detection. This class is used to create lasers both for the player and the enemy invaders.
Player Character: A class for the player character is created, defining its appearance, health, and the
ability to shoot lasers. It also manages the player's health and health bar.
Enemy Characters: An enemy class is defined for the invaders, specifying their appearance, movement,
shooting behavior, and collision detection with the player.
Collision Handling: The project implements collision detection for both lasers and enemy ships. When a
laser collides with an enemy, it reduces the enemy's health. If an enemy ship reaches the bottom of the
screen, the player loses a life.
Health and Scoring: The game has a health system for the player, starting with 3 lives, and it displays the
player's health on the top right of the screen. A scoring system is also implemented, where the player earns
100 points for each enemy ship destroyed.
Game Graphics: The project includes graphics for the background and game over screen, which is
displayed when the player loses.
Audio: Audio files, including intro music, laser shooting sounds, explosion sounds, and player sounds, are
incorporated into the game to enhance the gaming experience.
Game Loop: The main game loop handles player movements, shooting, enemy behavior, wave
progression, and checks for game over conditions. It runs the game until the player either runs out of lives
or health, displaying a "You Lost!!" message on the screen in case of defeat.
Main Menu: A simple main menu is provided where the player can start the game by pressing the mouse
button. 
