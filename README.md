Tutorial: Basket Catch Game (MakeCode Arcade)

This is a beginner-friendly MakeCode Arcade project built with Python.
The player controls a basket and tries to catch falling apples.
It’s designed as a tutorial to teach two core programming concepts:
✅ Conditions – making decisions with if statements
✅ Collisions – detecting when two sprites touch

🎮 How to Play
Move the basket left and right with the arrow keys (or joystick).
Apples fall from the top of the screen.
Catch an apple → your score increases.
Miss an apple → it resets and falls again.

Learning Goals
This project helps beginners understand:
1. Conditions
if apple.y > 120:
    apple.set_position(randint(0, 160), 0)
This condition checks if the apple has fallen past the bottom of the screen.
If true, the apple resets to the top.
2. Collisions
sprites.on_overlap(SpriteKind.player, SpriteKind.food, on_overlap)
This detects when the basket and apple collide.
When they overlap, the player scores a point.

Getting Started
Open MakeCode Arcade.
Select New Project → choose Python mode.
Copy-paste the code from this repository.
Press Play ▶️ to test the game.

Project Files
main.py → Game logic written in Python
README.md → Instructions and learning guide