# PROJECT FRONTIER — 星際拓荒
### Planetary Industrial Survival

A browser-playable, real-time sci-fi colony builder and automation game. No build step or external runtime dependencies are required.

## Play
Open **[index.html](index.html)** in a modern desktop browser, or enable GitHub Pages with **Settings → Pages → Deploy from a branch → main / root**.

## Core loop
1. Survey the planet and place miners on matching ore deposits.
2. Build solar and wind generators to supply the colony.
3. Process iron into alloy plates, then assemble electronic components.
4. Construct a research lab and unlock industrial technologies.
5. Expand battery capacity and build turrets before alien raids.
6. Balance power generation, consumption, resource stockpiles and production.

## Controls
- Click a tile to inspect it.
- Choose a construction item, then click a valid tile to place it.
- Select a building and use **拆除設施** to reclaim part of its materials.
- Belts can be placed and rotated; they mark logistics routes between industrial structures.
- Pause, change simulation speed, save, or reset from the system panel.

## Prototype 0.2.0
- 20 × 14 planetary grid with iron, copper, crystal, rock and water terrain.
- Ten construction types: miner, solar, wind, smelter, assembler, crystal drill, conveyor, battery, turret and research lab.
- Shared colony inventory with automated extraction and production recipes.
- Day/night power cycle, battery capacity, power demand and brownout behavior.
- Research tree with six technology upgrades.
- Escalating alien raids, base integrity and automated turret defense.
- Mission progression, event alerts and browser-local autosave.

## Development status
This is a playable foundation. The next vertical slice should make conveyor belts carry visible items between buildings, add fluid extraction and processing, expand the world through exploration, and introduce more varied alien units and defensive structures.

## Save data
Progress is stored in browser localStorage on the device and browser where the game is played. Clearing site data will remove the save.

## License
No license has been added. All rights remain with the repository owner unless a license is explicitly added.
