# CHIP8

This is a simple CHIP8 emulator written in C, using SDL2 for graphical rendering and input handling. The emulator supports loading and executing CHIP8 ROMs and provides basic features like emulation control and graphical output.

## Features

- Emulates a CHIP8 CPU
- Renders the CHIP8 graphics onto an SDL window
- Supports keyboard input to control the emulator (pause/resume functionality)
- Loads ROMs and executes them

## Prerequisites

Before you can compile and run the emulator, you'll need to have the following installed:

- **SDL2 library**: For handling graphics and input.
- **C compiler**: (e.g., GCC or Clang)

### Install SDL2 (Linux)
```bash
sudo apt-get install libsdl2-dev
```

## Compilation

To compile the CHIP8 emulator, run the following command:

```bash
gcc -o main main.c -lSDL2
```

## Running the Emulator

Once the emulator is compiled, you can run it by specifying a CHIP8 ROM. For example:

```bash
./main ROM_FILE
```

Replace ROM_FILE with the path to your CHIP8 ROM file.

## Controls

    Spacebar: Pause/Resume the emulation
    Esc: Close the emulator

## Debugging

If you compile the code with the DEBUG flag, the emulator will output detailed information about each instruction it executes:

```bash
gcc -o main main.c -DDEBUG -lSDL2
```
