# Next-Level
Ultimate Game Collection is a C++ desktop game suite built using SFML, featuring four classic games in one GUI application

# Ultimate Game Collection

A C++ desktop application built with SFML that includes four mini-games in a clean and interactive menu interface:

- 🪨 Rock Paper Scissors  
- ❌ Ultimate Tic Tac Toe  
- ⭕ Classic Tic Tac Toe  
- 🔢 Number Guessing Game

## Features

- Custom UI with smooth buttons, visual feedback, and game states
- SFML-based graphics with interactive mouse input
- Color-coded outcomes and animations
- Modular class-based game design

## Screenshots

> (Add screenshots of the menu and games if available)

## Requirements

- **C++17 or newer**
- **SFML 2.5+** (Graphics, Window, Audio, System)
- Compatible with Windows and Linux (tested on CachyOS)

## Build Instructions

### Linux (example for Arch-based)

```bash
sudo pacman -S sfml
g++ -std=c++17 -o GameCollection main.cpp -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
./GameCollection
```

Windows (MinGW)

    Install SFML and ensure sfml-xxx.dll are available

    Use the following compile command (adjust path as needed):
    ```
g++ -std=c++17 -IC:/SFML/include -LC:/SFML/lib -o GameCollection.exe main.cpp -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
```

Notes

    The font path is hardcoded to C:/Windows/Fonts/arial.ttf. You may want to change it to a relative path or embed a font in the repo.

    All logic is included in a single source file (Next-Level.cpp)

  
