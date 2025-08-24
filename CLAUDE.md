# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple snake game implemented as a single HTML file with embedded JavaScript. The entire game is contained in `index.html`.

## Architecture

- **Single file structure**: The game consists of only one file - `index.html`
- **Canvas-based rendering**: Uses HTML5 Canvas for drawing the game
- **Game loop**: Uses `setInterval()` for the main game loop at 200ms intervals
- **Keyboard controls**: Arrow keys control snake movement
- **Collision detection**: Handles wall collisions and self-collision

## Development

To run the game, simply open `index.html` in a web browser. No build process or dependencies required.

The game features:
- Snake movement with arrow keys
- Food spawning and collection
- Growth mechanics when eating food
- Game over detection and restart
- 20x20 pixel grid system on a 400x400 canvas
- use tailwind for design