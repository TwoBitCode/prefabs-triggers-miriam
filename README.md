# Space Shooter Game - Enhanced Features 🚀
Play the game on Itch.io: 

## Overview 🌌
This is an enhanced version of the Space Shooter game, originally developed during lectures. The improvements include:
- Dynamic display of the player's score, adapting to screen size and orientation.
- Circular world boundaries in the horizontal axis and closed vertical boundaries.

## Features Implemented 🛠️
### 1. **Dynamic Score Display** 💡
   - The player's score is displayed at a fixed position on the screen (e.g., the top-right corner).
   - The position adapts automatically to changes in screen size and orientation.
   - Implemented using the `Canvas` system in Unity, ensuring a responsive UI design.

  in code: I used changed the Numfield and LaserShooter code:
  - 
  -
  
### 2. **Circular Horizontal Boundaries** 🔄
   - The game world is now circular along the horizontal axis:
     - When the player reaches the right edge of the screen, they reappear on the left edge, and vice versa.
   - Closed boundaries on the vertical axis prevent the player from leaving the screen's top or bottom.

  in code: 
  
### 3. **Improved Game Experience 🎮**
   - Collision-based logic was implemented for boundary detection without relying on hardcoded values, ensuring scalability and maintainability.

