# Pong

## ⚠️ Archived Project Notice

This project is no longer maintained. Feel free to explore or fork the code, but it is provided as-is.

## Description

Welcome to my version of the classic Pong game implemented in Assembly 8086. This game will provide a nostalgic experience of the iconic pong game (when there aren't any major bugs). This game can be played single and as a duo.

<!-- ![Demo video of my pong game](/media/Pong.mp4) -->

![A 10 second video demonstrating my pong game made in assembly](/media/Pong.gif)

## Features

1. Singleplayer and multiplayer game modes
1. Paddle controls
1. Ball movement
1. Score tracking for each player
1. Game Over screen with winner announcement

## Controls

- Player 1 (left paddle):
    - Move up: `W` or `w`
    - Move down: `S` or `s`
- Player 2 (right paddle):
    - Move up: `O` or `o`
    - Move down: `L` or `l`
- General:
    - Exit game: `E` or `e`
    - Main menu: `M` or `m`

## Requirements

- DOSBox (DOS emulator)

## Installation

1. Install DOSBox on your system.
2. Download this git repository to your local machine.
3. Open DOSBox and mount the directory containing the game files.
```
mount C path/to/game/folder
```
Replace `path/to/game/folder` with the actual path to the game files.

4. Change to the mounted directory.
```
C:
```

## How to run

1. Inside DOSBox, navigate to the game directory.
```
cd src
```
2. Compile the assembly file
```
masm.exe /a game.asm
```
3. Link the object file
```
link game.obj
```
4. Run the game
```
game.exe
```
