# Scrolling Shooter Starter Project

## Project Overview

In this project, you will create your own **scrolling shooter game** using **Python**, **Pygame**, and **Object-Oriented Programming**.

You will build on the skills we have practised in class, including:

* Python classes and objects
* Constructors, attributes and methods
* Pygame game loops
* Keyboard input
* Sprite movement
* Collision detection
* Bullets and firing
* Score display
* Sound and music
* Graphics and backgrounds
* Scrolling backgrounds
* Simple menu/game states

The aim is not to create a huge game immediately. You should build your project in small stages and test each feature as you go.

---

## Project Folder Structure

Your project should be organised like this:

```text
scrolling-shooter/
│
├── main.py
├── README.md
│
├── images/
│   ├── player.png
│   ├── enemy.png
│   └── background.png
│
└── sounds/
    ├── shoot.wav
    └── music.mp3
```

You may add more files and folders later if your game becomes more advanced.

---

## How to Run the Game

1. Open the project folder in PyCharm or VS Code.
2. Make sure Pygame is installed.
3. Open `main.py`.
4. Run the program.

If Pygame is not installed, use:

```bash
pip install pygame
```

---

## Minimum Game Requirements

Your game should include:

* A working `Game` class
* A controllable `Player`
* At least one enemy type
* Player bullets
* Bullet and enemy collision detection
* A score display
* Sprite groups
* A background
* A clear game loop
* Code that is organised into separate classes

---

## Recommended Classes

You should aim to use these classes:

```text
Game
Player
Enemy
Bullet
Background
```

You may also add extra classes, such as:

```text
Menu
PowerUp
Explosion
HealthBar
EnemyBullet
```

---

## Suggested Development Order

Build your game step by step.

```text
1. Set up the Pygame window
2. Create the Game class
3. Add the Player class
4. Add player movement
5. Add the Bullet class
6. Add shooting
7. Add the Enemy class
8. Add collisions
9. Add the score display
10. Add images
11. Add sound and music
12. Add a scrolling background
13. Add a start menu
14. Add a game over screen
```

Test your game after each step.

---

## Controls

You can update this section once your controls are final.

```text
Arrow keys / WASD: Move the player
Space: Shoot
Enter: Start the game
Escape: Quit or return to menu
```

---

## Assets

You may use simple shapes at first. Later, you can replace them with images.

Suggested assets:

* Player spaceship
* Enemy spaceship
* Background image
* Bullet image or rectangle
* Shooting sound
* Background music

Make sure any images or sounds you use are suitable for school use and are either created by you or free to use.

---

## GitHub Commit Expectations

You should commit your work regularly.

A good commit message explains what changed.

Example:

```text
[feature] Add player movement

What I changed:
- Added keyboard controls for left, right, up and down
- Added screen boundary checks

Why I changed it:
- The player needs to move around the screen

Tested:
- [x] I ran the game
- [x] The game opened without errors
- [x] The movement worked as expected
```

Try to commit after each important step, not only at the end.

---

## Common Problems to Check

Before asking for help, check:

* Did you save your file?
* Did you spell the image or sound filename correctly?
* Is the image or sound in the correct folder?
* Did you add your sprite to the correct sprite group?
* Did you call `update()`?
* Did you call `draw()` or use `all_sprites.draw()`?
* Did you remember `pygame.display.flip()`?
* Did you remember `clock.tick(FPS)`?
* Did you run the game after making a small change?

---

## Reflection Questions

As you develop your game, think about:

1. What classes have I created?
2. What is each class responsible for?
3. Is my `Game` class controlling the whole project clearly?
4. Have I avoided putting everything into one large class?
5. Which features are working well?
6. What bugs still need to be fixed?
7. What feature should I add next?

---

## Success Criteria

Before submitting, check that:

* The game runs without errors.
* The code uses classes appropriately.
* The player can move.
* The player can shoot.
* Enemies appear on the screen.
* Bullets can hit enemies.
* The score changes correctly.
* The code is organised and readable.
* Images and sounds load correctly, if used.
* GitHub commits show clear progress over time.

---

## Notes

Start simple.

A working basic game is better than an unfinished complicated game.

Once the core game works, you can improve it with extra features such as health, levels, power-ups, menus, different enemy types, and better graphics.
