# Asteroids

A 2D reinterpretation of the classic *Asteroids* game with solid boundaries, physics-based collisions, and mouse-aimed shooting mechanics.

## 🕹️ Project Overview

This project is a browser-based **reimagining of the classic Asteroids game**, developed as a **group project**, with a focus on gameplay logic, collisions, and real-time interaction.

Unlike the original game, where objects wrap around the screen edges, this version introduces **solid boundaries**:
- The spaceship cannot cross the screen limits
- Asteroids bounce off the edges, creating a more constrained and tactical play area

The shooting system was redesigned to use **mouse-based aiming**, allowing players to shoot projectiles in the exact direction of the mouse click.

## ✨ Gameplay Features

- Solid screen boundaries with collision response
- Mouse-aimed shooting system
- Dynamic asteroid spawning and movement
- Rotating asteroids with individual axis rotation
- Lives system (3 lives)
- Pause menu with UI controls
- Ship customization (color selection)
- Game over screen with restart logic

## 👩‍💻 My Contributions

In this group project, I was primarily responsible for the **core gameplay logic and systems**, including:

- Asteroid spawning logic and movement behavior  
- Asteroid collision detection and response
- Asteroid rotation around their own axis
- Asteroid destruction logic:
  - When destroyed by the player, asteroids split into two smaller asteroids  
  - Smaller asteroids can be destroyed again, splitting once more
  - After the smallest asteroids are destroyed, they disappear completely
- Automatic respawn of asteroids when all on-screen asteroids are destroyed  
- Missile spawning logic
- Missile tracking system that follows the spaceship in real time  
  - Including real-time rotation of the missile sprite towards the ship  
- Missile is instantly destroyed after being shot by player
- Collision detection between:
  - Missiles and the spaceship  
  - Asteroids and the spaceship
- Implementation of a **lives system** (3 lives total)
  - Collision with asteroids or missiles removes one life  
- Game over logic:
  - Display of a “You Lose” screen  
  - Restart functionality that resets score and lives  
- Pause system:
  - Pause button in the top-left corner  
  - ESC key support  
  - Pause menu logic and visuals  
- Ship customization menu:
  - Allows changing the ship’s color (3 options)

## 🧰 Technologies Used

- JavaScript
- Three.js
- HTML5
- CSS3 
- Bootstrap (UI components only)

## 🎯 Project Context

This project was developed as part of an academic group assignment, focusing on:
- Real-time game logic
- Collision systems
- State management (pause, game over, restart)
- Player feedback and control responsiveness

## 🚀 How to open
URL: https://vivi4na02l.github.io/Asteroids/
