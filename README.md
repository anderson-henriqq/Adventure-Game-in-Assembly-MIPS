# Atari Adventure Remake in Assembly

This project is a non-faithful remake of the Atari game **Adventure**, developed using Assembly language for the MIPS architecture. It was created as a course project for the **Computer Architecture** class. The project was both challenging and rewarding, as working with a low-level language like Assembly pushed me to improve my problem-solving skills and deepen my understanding of how computers operate at a fundamental level.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Requirements](#requirements)
  - [Running the Game](#running-the-game)
- [How to Play](#how-to-play)
- [Technical Details](#technical-details)
- [Credits](#credits)

## Overview
This project is a simple 2D game inspired by **Adventure** for the Atari 2600. The game is built for the **MIPS Mars** simulator using its Bitmap Display feature, and controlled with keyboard inputs. The objective of the game is to move the character through the display using the keyboard.

## Features
- **Display resolution:** 512 x 256 px
- **Pixel unit size:** 4x4
- **Total pixels on screen:** 8192
- Player control using **W**, **A**, **S**, and **D** keys for movement

## Getting Started

### Requirements
- **MIPS Mars Simulator**: Make sure you have the MARS simulator included in this repository, or download the latest version [here](http://courses.missouristate.edu/KenVollmar/mars/).

### Running the Game
1. Open the **MARS** simulator from the repository.
2. Go to `Settings > Tools` and open **Bitmap Display**.
3. Configure the **Bitmap Display** with the following settings:
   - **Unit Width in Pixels:** 4
   - **Unit Height in Pixels:** 4
   - **Display:** 512 x 256
4. Click **Connect to MIPS**.
5. Open the **Keyboard and Display MMIO Simulator** tool.
6. Click **Connect to MIPS** to enable keyboard input.
7. Load and execute the program.

## How to Play
- Use the following keys to move your character:
  - **W**: Move up
  - **A**: Move left
  - **S**: Move down
  - **D**: Move right

Navigate through the display, representing the game's environment, and enjoy the challenge of this minimalist adventure.

## Technical Details
- The game leverages the MIPS architecture and is written entirely in assembly language.
- The graphics are managed via the **Bitmap Display** tool within the MARS simulator, and keyboard inputs are read through the **MMIO Simulator**.
- Due to the low-level nature of the project, efficient memory management and direct control over hardware components are key elements of this program.

## Credits
Developed by Anderson as part of the **Computer Architecture** course in the **Análise e Desenvolvimento de Sistemas** program.
