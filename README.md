SFML 2048 Game (C++)
A desktop implementation of the classic 2048 puzzle game developed using C++ and the SFML graphics library.
This project focuses on game animation, object-oriented design, and real-time rendering.
________________________________________
Features
•	Classic 2048 gameplay
•	Smooth tile sliding animation
•	Winning screen & sound effect
•	Simple and clean game interface
•	Object-oriented game structure
•	Lightweight C++ implementation using SFML
________________________________________
Controls
Key	Action
↑	Move tiles up
↓	Move tiles down
←	Move tiles left
→	Move tiles right
Tiles with the same value will merge when they collide.
________________________________________
Game Rules
•	The board size is 4 × 4
•	After each move, a new tile (2 or 4) appears
•	Merge tiles to create larger numbers
•	Reach 2048 tile to win
•	Game ends when no valid moves remain
________________________________________
Project Structure
SFML-2048/
│
├── SFMLGameAnimated.cpp
├── SFMLGameAnimated.h
├── tile.h
│
├── tile2.png
├── tile4.png
├── tile8.png
├── tile16.png
├── tile32.png
├── tile64.png
├── tile128.png
├── tile256.png
├── tile512.png
├── tile1024.png
├── tile2048.png
│
├── win.png
├── win_sound.wav
│
├── SFML_game.cbp
├── SFML_game.layout
└── README.md
________________________________________
 Requirements
•	C++ Compiler (MinGW / MSVC / G++)
•	SFML 2.x Library
Download SFML:
https://www.sfml-dev.org/
________________________________________
Build & Run
Example (MinGW):
g++ SFMLGameAnimated.cpp -o game ^
-lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
Run:
game.exe
________________________________________
 Future Improvements
•	Add restart button
•	Improve animation performance
________________________________________
 Author
Nguyen Ba Duc Nhan
Student project – learning Game Development with C++ & SFML
________________________________________
If you like this project, please consider giving it a star.
