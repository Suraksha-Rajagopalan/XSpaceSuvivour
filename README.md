<div align="center"><h1>XSpaceSuvivour</h1></div>

This Python code is a simple 2D space shooter game using the Pygame library. The game is called "XSpace Survivor." Here's a summary of its functionality:

The code sets up the Pygame window with a size of 1000x800 pixels and loads various images for the player's spaceship, enemies (UFOs), and bullets. It also loads background music and sound effects for shooting and collision.

The player controls a spaceship using the left and right arrow keys. Pressing the spacebar fires a bullet from the spaceship.

There are eight enemies (UFOs) randomly placed on the screen, and they move horizontally back and forth. They also move down the screen when they reach a certain point.

When the player's bullet collides with an enemy UFO, both the bullet and the enemy disappear. A collision sound effect plays, and the player's score increases by one.

The game displays the player's score on the screen at the top left corner.

If any of the enemies reach a certain height on the screen, the game ends, and a "GAME OVER" message is displayed on the screen.

The game loop continuously updates the screen, checking for player input, moving the player, enemies, and bullets, and handling collisions.


