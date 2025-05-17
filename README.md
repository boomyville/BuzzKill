# Buzzkill

## Overview
Buzzkill is a fly-swatting game inspired by the classic mini-game from Mario Paint on the Super Nintendo. The player controls a fly swatter and must swat flies before they escape from the screen. The game features multiple levels with increasing difficulty, a scoring system, and lives.

## Game Features
- **Fly Movement**: Flies move in semi-random patterns across the screen
- **Collision Detection**: Precise hit detection between the swatter and flies
- **Scoring System**: Points awarded for each successfully swatted fly
- **Lives System**: Players lose lives when flies escape
- **Level Progression**: Multiple levels with increasing difficulty
- **Timer**: Each level has a time limit
- **Accuracy Tracking**: Game tracks swatter swing accuracy

## Controls
- **Mouse Movement**: Move the fly swatter
- **Mouse Click**: Swing the swatter to hit flies

## Game Mechanics
- Flies spawn every few seconds
- Each level lasts 20 seconds
- Higher levels spawn flies more frequently and flies move faster
- Player gains an extra life at the start of each new level (maximum 5)
- Game ends when all lives are lost

## Technical Details
- Written in Processing
- Uses object-oriented programming concepts
- Features dynamic fly movement using noise functions
- Implements image rotation for realistic fly movement
- Collision detection using distance calculation

## Setup Instructions
1. Install Processing from [processing.org](https://processing.org/)
2. Open the Buzzkill.pde file in Processing
3. Ensure the following image files are in the "data" folder:
   - fly.png
   - flybye.png
   - swatter.png
   - swatted.png
4. Run the sketch by clicking the play button in Processing

## Debugging
The game includes a debug mode that can be enabled by setting the `debug` variable to `true`. Debug mode shows:
- Collision radius circles
- Fly movement direction lines
- Debug messages in the top-right corner

## Credits
- Developed by Kevin Teong
- For COSC 101 - Software Development Studio 1
- Student ID: 220295079
- Inspired by the fly swatting game from Mario Paint on the Super Nintendo
