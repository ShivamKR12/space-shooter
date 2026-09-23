# Space Shooter

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![pygame-ce](https://img.shields.io/badge/Library-pygame--ce-1D9BF0?logo=pygame&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)
![GitHub Actions](https://img.shields.io/badge/CI-GitHub%20Actions-2088FF?logo=github-actions&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)

</div>



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
