# Donkey Kong Game (C++ Console)

Donkey Kong style console game written in **C++**, as part of an academic project.

The game implements Mario, ghosts, barrels and full game logic using **OOP**, inheritance
and polymorphism. Levels are loaded from files and the game supports multiple screens.

## 🎮 Features

- Mario movement on platforms and ladders  
- Jump logic with space restrictions (needs 2 spaces up and 4 forward)  
- Falling, collision detection and death handling  
- Different ghost types (basic, climbing, etc.)  
- Barrels and obstacles moving on the board  
- Score system and bonus points  
- Pause & resume (ESC to pause, `9` to return to menu)  
- Death reason feedback: when Mario dies, the game pauses and shows where and why
- Hammer Mechanic: The hammer appears only once per screen.  
   If Mario gets hit while holding it, the hammer is lost.
- Surprise Feature:Each level includes a hidden bonus spot (`?` symbol). 

## 📁 Project Structure

- `*.cpp`, `*.h` – game logic and classes (Mario, Ghost, Barrel, Board, Game, Results, etc.)
- `dkong_0X.screen` – level layout files
- `dkong_0X.steps` / `dkong_0X.result` – history and expected results for testing
- `file_format.txt` – description of the level file format
- `DonkeyKong-ex1.sln` / `.vcxproj` – Visual Studio solution and project files

## ▶️ How to run

1. Open `DonkeyKong-ex1.sln` in **Visual Studio** (Windows).
2. Set the project as `Startup Project` if needed.
3. Build the solution (`Ctrl+Shift+B`).
4. Run the game (`F5`).

## Authors

- **Ben Garusi**
- **Gal Libal**
