# uru-programming-1-blackjack

A Blackjack terminal game written in C++, the theory final project of the Programming I course of the Computer Science career at Universidad Rafael Urdaneta, Maracaibo, Venezuela.

**Note:** This repository is archived and read-only.

## Build

Clone the repository and build from its root with either option. For a better experience, run the game with the terminal in fullscreen.

**G++** (requires the MinGW compiler on Windows):

```bash
# Windows
g++ -o bin\Blackjack.exe src\main.cpp src\lib\cartas.cpp src\lib\clases.cpp src\lib\terminal.cpp

# Linux
g++ -o bin/Blackjack.exe src/main.cpp src/lib/cartas.cpp src/lib/clases.cpp src/lib/terminal.cpp
```

**CMake** (requires CMake and Make; the generator below is MinGW Makefiles). From the `bin` folder:

```bash
cmake -S ../ -G "MinGW Makefiles" -B ./ && make
```

Then run `Blackjack.exe`.

## Project structure

- **`src/main.cpp`** — Game entry point.
- **`src/lib/cartas.*`** — Cards.
- **`src/lib/clases.*`** — Game classes.
- **`src/lib/terminal.*`** — Terminal helpers.

## Developers

- [ralvarezdev](https://github.com/ralvarezdev) — Ramón Álvarez
