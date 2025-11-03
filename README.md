# The Lost Knight
A 2D Adventure RPG built in C++ using SDL3

------------------------------

### Overview

The Lost Knight is a 2D adventure RPG built entirely in C++ using SDL3 for the COMP3016 Immersive Game Technologies module.

The game follows a lone knight who awakens in a world he has never seen before, with no memory of the past. You must explore the town, uncover fragments of forgotten memories and gradually piece together the truth of what happened to the lone knight.

Rather than relying on external engines, The Lost Knight was developed from scratch to highlight fundamental programming skills in:
- Efficient memory and file I/O management
- Dynamic map loading and event triggers
- Clean OOP architecture
- Immersive narrative-driven design

------------------------------

### Youtube Video


------------------------------

### Gameplay Description

Objective:
Explore the world, uncover hidden memories and restore fragments of the knight's past.

Controls:
W / A / S / D - Move
Space / F - Interact

Core Features:
Exploration - Traverse an open 2D world and interact with objects, items and NPCs.
Progression System - The more mysteries and secrets you uncover, the more you remember, allowing your experience bar to increase to level up attributes.
File-Driven Data - Maps, dialogue and player stats are loaded from external text files for easier scalability and modification.

------------------------------

### Game Mechanics

Exploration System: The world map is read from file (map.txt), generating terrain, barriers and interactable elements dynamically.
Event Triggers: Certain tiles and areas trigger story events or memory fragments.

------------------------------

### Dependencies

Language: C++
Libraries: SDL3, SDL3_image and CMake

------------------------------

### Use of AI

Generative AI tools (such as ChatGPT) were used in an assistive role to:
- Debug and structure game logic (OOP patterns and file management)
- Generate placeholder sprites and backgrounds

------------------------------

### Exception Handling and Testing

- Input validation was used in case of missing textures or failed asset loads
- Fallback textures are used when assets are missing or unavailable.

------------------------------

### How to Run

1. Download and extract the Game.zip file.
2. Make sure these folders are included with the download:

------------------------------

### Evaluation

This project demonstrates my understanding of unmanaged C++ programming, OOP architecture and file-driven game design within the SDL3 framework. The project achieves its core goals of building a modular, expandable 2D world where players can explore and uncover narrative elements through interactive systems.

Developing this project has strengthened my ability to structure code effectively and handle data dynamically through external files. I also gained valuable lessons in debugging, optimisation and implementing clean reusable code.

If I were to continue this project, I would focus on expanding the world with storylines and interacive NPCs, as well as an event system to enhance immersion. I would also add the combat system to add more enjoyablity to the game.
