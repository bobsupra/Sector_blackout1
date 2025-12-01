# Sector Blackout

**Sector Blackout** is a First-Person Survival Horror project built in Unreal Engine 5. The game features flashlight mechanics, weapon equipping/unequipping logic, and enemy AI tracking.

## ⚠️ Build & Installation Note

**There is currently no playable executable (.exe / .app) available for download.**

We developed this project using macOS. Due to technical limitations and packaging errors specific to the Mac version of Unreal Engine, we were **unable to package a final executable build**.

To play or test the game, you must download the project source code and open the `.uproject` file directly in the Unreal Editor.

## Gameplay Status & Known Issues

Although the project faced technical hurdles, we implemented a complete game flow:

*   **Game Loop:** The project contains a fully functional **Start** and **Ending** sequence.
*   **Weapon System:** The equipping and unequipping logic is fully functional. The player can toggle the weapon (G Key) and it correctly interacts with the flashlight system and animation blueprints.
*   **Shooting Mechanic:** Unfortunately, **the actual firing mechanic is currently not working.** While the player can hold and aim the gun, the damage/projectile logic encountered bugs in the final version.

## Project Scope & Cut Content

The original vision for **Sector Blackout** was highly ambitious, featuring a massive map and complex survival elements. However, during development, we realized the scope was too large for our time constraints.

*   **Map Size:** We created a very large map, but filling it with meaningful gameplay proved difficult within the deadline.
*   **Cut Content:** To ensure the core mechanics (lighting, AI) worked, we had to cut a significant amount of planned content. The current version focuses on the technical implementation of the player controller and enemy interaction rather than a full open-world experience.

## Development Challenges

This project faced significant hurdles regarding team coordination. We experienced persistent difficulties communicating with a specific team member, which created bottlenecks in development. This lack of communication made merging assets and coordinating tasks much more difficult than anticipated, contributing to the reduced scope of the final submission.

## Features Implemented

*   **Inventory Logic:** Toggleable Pistol with "Equip/Unequip" logic (G Key).
*   **Flashlight System:** Handheld flashlight that automatically unequips when using a weapon (F Key).
*   **Enemy AI:** Monsters that patrol and chase the player based on line-of-sight logic.
*   **Animation Blending:** Layered animation blending for holding weapons while moving.
