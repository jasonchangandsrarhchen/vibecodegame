# NEON ABYSS PROTOCOL
### 霓虹深淵：戰術協定

A single-player, squad-based, turn-based tactical roguelite prototype.

## Play the tactical prototype
Open **[index.html](index.html)** on the `turn-based-reboot` branch, or download that file and open it in a modern desktop browser. No build step or external dependencies are required.

## Current playable systems
- 10 × 8 tactical grid.
- Three operatives: Phantom, Bastion and Engineer.
- 2 AP per operative each player turn.
- Move up to 3 tiles for 1 AP; basic attack costs 1 AP.
- Phantom: teleport strike; Bastion: team damage reduction; Engineer: deployable auto-turret.
- Four enemy units with visible intent previews and an enemy phase.
- Walls block line of sight; cover reduces incoming damage.
- Victory/defeat and restart loop.

## Controls
- Click a friendly operative to select it.
- Click an empty reachable tile to move.
- Click an enemy to attack if it is in range and line of sight.
- Use the selected operative's skill button; click a target tile/enemy if prompted.
- End Turn to resolve enemy actions.
- Wait spends the selected operative's remaining AP.

## Development branch
The reboot is being developed on **turn-based-reboot**. The previous real-time action prototype remains preserved on **main**.

## Project documents
- [Turn-Based Game Design](docs/GAME_DESIGN.md)
- [Development Roadmap](docs/ROADMAP.md)

No license has been added yet.
