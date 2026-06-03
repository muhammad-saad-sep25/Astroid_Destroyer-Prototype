# Asteroid Destroyer

Asteroid Destroyer is a 2D arcade-style space shooter built using Python and Pygame. The game features smooth movement, wave-based difficulty, a menu system with settings, and dynamic asteroid spawning with increasing challenge over time.

The player controls a spaceship and must survive endless waves of asteroids while shooting them down to increase score.

---

## Gameplay Overview

You are a spaceship pilot navigating through deep space. Asteroids spawn continuously from the right side of the screen and move toward you with varying speed, size, and rotation.

Your mission:

- Destroy asteroids using bullets  
- Avoid collisions with asteroids  
- Survive as long as possible  
- Progress through increasing difficulty waves  
- Achieve the highest score possible  

---

## Features

### Core Gameplay
- Smooth player movement using WASD controls
- Shooting system using spacebar or mouse input
- Bullet-based combat mechanics
- Collision detection between player and asteroids
- Lives-based survival system

### Asteroid System
- Random asteroid sizes between 30 and 70 pixels
- Variable movement speeds
- Optional diagonal movement behavior
- Rotating asteroid sprites for visual variation
- Automatic cleanup of off-screen objects

### Visual System
- Animated starfield background
- Smooth sprite rendering and scaling
- Rotating asteroid visuals
- Clean 2D space environment

### Wave System
- Wave-based progression system
- Increasing asteroid spawn rate over time
- Difficulty increases every 30 seconds

### Audio System
- Background music loop
- Shooting sound effects
- Explosion sound effects
- Adjustable volume controls (master, music, SFX)

### Menu System
- Interactive main menu
- Settings menu with real-time adjustments
- Keyboard navigation support
- Volume configuration system

### Game Over System
- Lives-based game over condition
- Final score display
- Automatic restart after delay

---

## Controls

| Action | Key / Input |
|--------|------------|
| Move Up | W |
| Move Down | S |
| Move Left | A |
| Move Right | D |
| Shoot | Spacebar / Left Mouse Button |
| Navigate Menu | Arrow Keys |
| Select Menu Option | Enter |
| Adjust Settings | Left / Right Arrow Keys |

---

## Project Structure

```bash
Asteroid-Destroyer/
│
├── main.py              # Entry point
├── game.py              # Main game loop and logic
├── player.py            # Player spaceship system
├── asteroid.py          # Asteroid behavior system
├── bullet.py            # Bullet mechanics
├── menu.py              # Main menu and settings system
├── settings.py          # Game constants and configuration
│
├── assets/
│   ├── Pngs/
│   │   ├── player.png
│   │   ├── asteroid.png
│   │
│   ├── sounds/
│   │   ├── Music.mp3
│   │   ├── shoot.mp3
│   │   ├── Explosion.mp3
│
└── README.md
