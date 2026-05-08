# Space Shooter

A 2D arcade-style space shooter game built with Python and the Pygame library. Navigate your ship through the endless void and survive as long as possible by dodging and destroying incoming meteors!

## Features
- **Player Movement:** Smooth 8-way directional movement using keyboard controls.
- **Combat System:** Shoot lasers with a built-in cooldown mechanic to destroy obstacles.
- **Dynamic Enemies:** Meteors spawn continuously with randomized speeds, rotation, and falling paths.
- **Animations & Audio:** Features pixel-perfect collision detection, animated explosion sequences, background music, and sound effects.
- **Scoring System:** Live score tracking based on how long you survive.

## Prerequisites
Make sure you have Python 3.x installed on your system. You will also need the `pygame-ce` library.

Install Pygame using pip:
```bash
pip install pygame-ce
```

## Installation & Setup
1. Clone or download this project to your local machine.
2. Ensure the following directory structure exists with the required game assets:
   - `images/` containing: `player.png`, `star.png`, `meteor.png`, `laser.png`, `Oxanium-Bold.ttf`
   - `images/explosion/` containing explosion animation frames from `0.png` to `20.png`
   - `audio/` containing: `laser.wav`, `explosion.wav`, `game_music.wav`
   - `code/` containing `main.py`
3. Open your terminal or command prompt and navigate to the project root directory.

## How to Play
Run the game by executing the main Python script:
```bash
python code/main.py
```

### Controls
- **Arrow Keys (`Up`, `Down`, `Left`, `Right`):** Move the spaceship.
- **`Spacebar`:** Shoot lasers.

### Objective
Shoot down the meteors to clear a path and survive for as long as possible! Your score increases the longer you stay alive. If your spaceship collides with a meteor, it's game over!