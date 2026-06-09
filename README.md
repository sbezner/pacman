# Pac-Man

A classic Pac-Man clone in a single, self-contained HTML file — no build step, no
dependencies. Just open `pacman.html` in any modern browser.

## Play

- **Desktop:** double-click `pacman.html`, or run `open pacman.html` (macOS).
- **Phone / tablet:** the game auto-detects touch devices and shows an on-screen
  D-pad plus swipe controls.

## Controls

| Action | Desktop | Touch |
| --- | --- | --- |
| Move | Arrow keys or WASD | On-screen D-pad, or swipe the maze |
| Pause | `P` | PAUSE button |
| Mute | `M` | MUTE button |

## Features

- The classic 28×31 maze with pellets, power pellets, and wrap-around side tunnels.
- All four ghosts with their authentic personalities (Blinky, Pinky, Inky, Clyde),
  plus scatter/chase cycles and frightened mode with combo scoring (200→400→800→1600).
- Fully synthesized sound via the Web Audio API (no audio files).
- Responsive layout with automatic mobile/tablet touch controls.
- High score saved in the browser's local storage.
