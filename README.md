# Tank Bot

A complete, playable web browser game titled **Tank Bot** built with Phaser 3.

## Core Mechanics

- **Player**: A tank controlled by WASD or Arrow Keys. It starts with 100% Health.
- **Weaponry**: Three selectable firing modes (Keyboard 1, 2, 3):
  - **Small**: 10% Damage, No Cooldown
  - **Medium**: 20% Damage, 1s Cooldown
  - **Max**: 30% Damage, 3s Cooldown
- **Enemies**: "Armor Bots" spawn every 5 seconds from the screen edges. Each has 100% Armor that visually decreases as it drops.
- **Controls**:
  - **WASD / Arrow Keys**: Move and rotate the tank.
  - **1, 2, 3**: Switch weapon modes.
  - **Spacebar**: Fire.
  - **Mouse Click**: Restart game on Game Over.

## Technical Requirements

- **Engine**: Phaser 3 (latest CDN) for physics and rendering.
- **Assets**: Uses geometric shapes for reliable rendering and Phaser Labs for sound effects.
- **UI**: Persistent HUD showing Player Health, Current Weapon, and Score.

## How to Play

Simply open `index.html` in any modern web browser to start playing.
