# 2D Car Racing Game

A simple yet engaging 2D car racing game developed in C++ using OpenGL and GLUT. The player controls a car in a top-down view and must avoid oncoming traffic while accumulating points. 

## 🎮 How to Play

- **Start Game**: Press `SPACE`
- **Move Car**:  
  - `LEFT ARROW`: Move left  
  - `RIGHT ARROW`: Move right  
- **Control Speed**:  
  - `UP ARROW`: Increase speed  
  - `DOWN ARROW`: Decrease speed  
- **Exit**: Press `ESC`

## 🕹️ Game Features

- Top-down 2D car racing
- Increasing difficulty as score increases
- Score tracking based on distance
- Collision detection
- Simple physics for movement
- In-game HUD (score, speed, level)
- Main menu and Game Over screens
- Colorful visuals with animated environment

## 🔧 Technologies Used

- C++
- OpenGL
- GLUT (OpenGL Utility Toolkit)

## 📦 Functions Overview

| Function Name       | Description |
|---------------------|-------------|
| `renderBitmapString` | Renders text on the screen using GLUT bitmap font |
| `tree`               | Draws roadside trees |
| `startGame`          | Main game loop with collision and scoring |
| `fristDesign`        | Main menu and instruction screen |
| `display`            | Decides screen view based on game state |
| `spe_key`            | Handles special key inputs (arrows) |
| `processKeys`        | Handles general key input (e.g. SPACE, ESC) |
| `timer`              | Manages frame rate updates |
| `main`               | Program entry point and game loop initialization |

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/c08f85dc-8a73-490c-bcd6-f680cdb74436)

![image](https://github.com/user-attachments/assets/447d4b54-0343-4bc4-a761-c0243cc41fed)

## 📚 References

- [OpenGL Documentation](https://www.khronos.org/opengl/wiki/)
- [GLUT Library](https://www.opengl.org/resources/libraries/glut/)
- [Game Programming Patterns](https://gameprogrammingpatterns.com/)
- [2D Graphics with Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_animations)
- [2D Collision Detection](https://developer.mozilla.org/en-US/docs/Games/Techniques/2D_collision_detection)
- [C++ Programming](https://learn.microsoft.com/en-us/cpp/cpp/)

---
