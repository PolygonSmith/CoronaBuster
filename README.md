# CoronaBuster
Programming and artwork by Michael Hintermeister

**Introduction:**
  As my final project, I chose to make a space invaders style projectile shooter, using P5.JS. The game features MediBot, a nanobot sent into the patient's body to fight the coronavirus particles. The sprites for all assets were modeled and textured in Blender, and edited using Adobe Photoshop to appropriately fit onscreen. p5.collide was used to add functional collision detection to the game. It was fun to incorporate my experience in the 3d realm into this 2d project, much like how Donkey Kong SNES created sprites using rendered video of (at the time) high quality 3d models.
  
  **Controls:**
  - Right Arrow = Move Right
  - Left Arrow = Move Left
  - Mouse (1 or 2) = Fire
  
  **To Play:**
  Download the repository and run in browser using Web Server For Chrome.
  
  **Goals**

  **Accomplished:**
  - Player movement is smooth, with seamless wraparound
  - Projectiles are functional, with prerendered sprites
  - Moving targets are decorated with prerendered sprites, and collision detection is fully functional
  - Game is overall well optimized, and projectiles deleting from their arrays as they exit the canvas.
  
  **Abandoned:**
  - A timer was planned to stop when all viron particles were destroyed, and the game was finished, however due to the complications with projectile movement early on in the project, complications with collision detection near the end of the project, and finally implementation of sprite assets, the timer was ultimately abandoned due to time constraints.
  - Initially I wanted to experiment with blendmodes and colormodes, however the goal was abandoned in favor of prerendered sprites, as a stylistic decision.
