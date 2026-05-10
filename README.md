# CosmicDriversV2.0

## Project Overview
This space-themed game, built with Pygame, challenges players to pilot a rocket through a hazardous starfield. The objective is to collect all randomly spawned stars while navigating around unpredictable meteor showers.

## Evolution of the Project
This is the second iteration of my game development journey. While the first version focused on core logic, this project dives deeper into asset management and interactive mechanics:

Dynamic Sprite Manipulation: Implemented directional movement by switching rocket assets based on key inputs.

Asset Interaction: Developed logic for star collection, real-time score tracking, and collision detection.

Audio & Visuals: Integrated background music, custom .ttf typography, and dynamic "Win/Loss" screens that trigger based on game state.

## Important Notes
**Collision Hitboxes:** As this was my first time working with custom transparent assets, players might experience "phantom collisions." The hitbox logic is slightly larger than the visual assets, which can occasionally cause a game-over even if the rocket doesn't visibly touch a meteor. Similarly, star collection may occasionally fail to register.

**Resolution & Responsiveness:** The game window is locked at 1000x625. This specific resolution was chosen to match the fixed scale of the assets (logo, buttons, and environment) to ensure the visual layout remains consistent and polished.

Enjoy playing and feel free to explore the code!

## example of a match:

<img width="1317" height="823" alt="image" src="https://github.com/user-attachments/assets/f1fd4cca-3f85-4380-8ac4-a9ac2e757fd2" />
