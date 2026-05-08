Dante's Descent

A 2D top-down action game built from scratch using Lua and the LÖVE2D framework. This project was developed as an academic exercise in game design, programming logic, and asset management.

 The Story
Loosely inspired by Dante Alighieri's *Divine Comedy*, the game places the player in the shoes of Dante, who has just spawned in the depths of Hell. 
To progress, Dante must navigate a treacherous landscape, fight off demonic guardians, and collect 10 of Beatrice's scattered tears. Once all tears are collected, Beatrice is summoned to the map, and reaching her triggers a successful rescue. 

Core Features
* **Custom Environments:** Hellscape map built and integrated using the **Tiled** map editor.
* **Combat Mechanics:** Active hit-box collision and combat systems featuring distinct enemy types, including Skeletons and Minotaurs that guard the tears.
* **Item Collection:** Dynamic progression loop where gathering 10 tears triggers a map-altering state (spawning the rescue target).
* **Collision Detection:** Programmed physics and boundaries to handle player movement, enemy damage, and win-state triggers upon colliding with Beatrice.

Technologies Used
* **Language:** Lua
* **Framework:** LÖVE2D
* **Level Design:** Tiled Map Editor

How to Run the Game
1. Ensure you have the [LÖVE framework](https://love2d.org/) installed on your machine and lua.
2. Clone or download this repository.
3. Drag the project folder directly onto the `love.exe` shortcut, or run it via terminal/command prompt from the directory:
   ```bash
   love .

   Developed by Giorgi Iremadze.
