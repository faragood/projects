# Software Development: "Don't be late!" Video Game

## Overview
This repository features "Don't be late!", a custom multi-level 2D application developed to help university freshmen navigate the campus. The game challenges players to reach specific classrooms across four floors within strict time limits while avoiding obstacles. 

## Project Links
* **Full Project Repository:** [GitHub - Lazynx/game-jam](https://github.com/Lazynx/game-jam)
* **Project Presentation:** [View on Canva](https://www.canva.com/design/DAGCyqvJbBY/MAYMGPMIRuYV8D5mWF1ftQ/view?utm_content=DAGCyqvJbBY&utm_campaign=designshare&utm_medium=link&utm_source=editor)

## Software & Technologies Used
* **Programming Language:** Python
* **Game Engine/Library:** PyGame
* **Data Management:** Custom Database Architecture

## Key Features & Engineering Highlights

### 1. Game Mechanics & State Management
* Implemented a four-level progression system with decreasing time constraints (ranging from 120 seconds to 60 seconds) and 8 distinct transition states.
* Engineered dynamic map editing mechanics, allowing users to modify the placement of objects and install or delete walls to alter player movement.

### 2. Interactive Quiz Logic
* Integrated in-game quizzes and a final exam focused on Python and PyGame.
* Developed logic to calculate a final GPA based on quiz results, saving the highest score to the database.

### 3. Dynamic Database Processing
* Built a custom database capable of processing 45,000 rows and managing over 10,000 different in-game objects.
* Configured the database to persistently track and remember any map edits and state changes after the game concludes.

### 4. Structured Code Architecture
* Developed a modular game loop consisting of over 1,200 lines of code.
* Separated logic into distinct modules: main game logic (820 lines), survey/quiz systems (228 lines), and an unlockable "Extra Game" space mini-game (229 lines).
