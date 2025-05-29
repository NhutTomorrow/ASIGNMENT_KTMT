# Gomoku Game - Attention

## Table of Contents
1. [Introduction](#introduction)
2. [System Requirements](#system-requirements)
3. [Installation](#installation)
4. [Attention](#attention)
6. [How to Play](#how-to-play)


## Introduction
Gomoku (Five in a Row) implemented in MIPS assembly. Two players alternate placing stones (X/O) on a 15×15 board.

## System Requirements
- MARS MIPS simulator 4.5+
- Java Runtime Environment

## ATTENTION (IMPORTANT)
- MARS MIPS simulator must be placed in the same location as the game_data file 
- To be able to get the data for "quit game"  funtion  and run the program correctly.
- This attention is mainly for the quit game function. When you press quit game in the options menu. When running the program again, a prompt will appear that you have a previous game to play again.
- When you choose to play the OLD GAME, the program will get data from the file "game_data"  that saves the previous game data to continue that game.
## HOW TO PLAY
- Choose time playing enter "ok" or "not ok"
- Choose first player enter "1" or "2"
- In your turn: 
    * You can enter a,b to make a move( with 0<= a,b <= 9)
    * Or you can enter "pause" to go to the options menu contain. Then choose your options.
    
## Installation
```bash
# Clone repository (if available)
git clone https://github.com/yourusername/mips-gomoku.git
cd mips-gomoku


