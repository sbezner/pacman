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
- **Bonus fruit** appears below the ghost house after enough pellets are eaten,
  rising in value as you climb levels (cherry → strawberry → orange → …).
- **Floating score popups** and a brief action freeze when you eat a ghost.
- **Per-level difficulty curve:** ghosts speed up (faster than Pac-Man) and the
  power-pellet frightened time shrinks each level. A LEVEL indicator shows progress.
- **Death spin animation** and a blue/white **maze flash** on clearing a level.
- Fully synthesized sound via the Web Audio API (no audio files): waka chomps,
  power-pellet, ghost-eat, fruit, and death effects, plus an intro jingle.
- Responsive layout with automatic mobile/tablet touch controls — a draggable
  arcade joystick plus swipe steering, with haptic feedback where supported.
- High score saved in the browser's local storage.
