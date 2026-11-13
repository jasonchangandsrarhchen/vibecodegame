# NEON ABYSS PROTOCOL — Turn-Based Tactical Roguelite
Version 2.0 · Rebooted design baseline

## Product direction
A single-player, squad-based, turn-based tactical roguelite in a neon cyberpunk megacity. The real-time action prototype is superseded by this design. The new branch is intentionally isolated so the previous prototype remains intact on main.

## Core fantasy
Lead a three-operative strike team through hostile sectors controlled by the rogue AI NEXUS. Every turn is a tactical puzzle: reposition, exploit cover, coordinate abilities, predict enemy intent and create elemental chain reactions.

## Design pillars
1. Readable tactical decisions — every enemy telegraphs its next action before the player commits.
2. Squad synergy — three operatives combine distinct roles and abilities.
3. Position matters — cover, line of sight, range, chokepoints and flanking matter more than raw stats.
4. Build freedom — equipment and modules create cross-role synergies; characters are not locked to one damage element.
5. Roguelite risk — branch through rooms, choose rewards and decide when to extract.
6. Fair information — no hidden enemy action resolution; enemy intent is visible and explainable.

## Battle format
- Grid battlefield, initially 10 columns × 8 rows.
- Fixed top-down tactical presentation; clear square grid in the first prototype.
- Player squad: three operatives deployed together.
- Each operative receives 2 action points (AP) per player turn.
- Move costs 1 AP; basic attack costs 1 AP; major skill usually costs 2 AP; interact costs 1 AP.
- An operative may move and attack in one turn, attack twice if weapon permits, or spend AP on a tactical skill.
- After all operatives act or the player presses End Turn, enemies execute their telegraphed intent.
- The player can inspect units and enemies before committing actions.

## Position and battlefield rules
- Orthogonal movement initially; diagonal movement may be introduced as a module.
- Obstacles block movement and line of sight.
- Cover reduces incoming ranged damage; heavy cover blocks shots.
- Melee/rush enemies threaten adjacent tiles.
- Later systems: elevation, destructible cover, hazards, overwatch cones, flanking and environmental interactions.

## Operatives
Four selectable characters; deploy three per mission.

| Operative | Tactical role | Signature skill |
|---|---|---|
| PHANTOM / 幽影 | Scout, flank, precision damage | Phase Shift: reposition through threatened lanes and mark a target |
| BASTION / 堡壘 | Tank, protect allies, hold chokepoints | Aegis Wall: deploy directional cover and draw enemy fire |
| ENGINEER / 工程師 | Area control, deployables | Sentry Drone: deploy a turret that fires during enemy phase |
| HACKER / 駭客 | Disable, manipulate machines | System Breach: interrupt or redirect a machine enemy's intent |

Character identity comes from AP-efficient abilities and passive traits, not weapon restrictions.

## Weapons and gear
Weapon families include energy sidearms, shotguns, pulse rifles, rail weapons, flamers, launchers and control tools. Gear alters tactical rules (pierce cover, chain to adjacent targets, suppress, mark, push, create hazards) rather than only increasing damage. Initial prototype equipment remains small to validate tactical feel.

## Status and synergy families
- Electromagnetic: chain damage, stun, interrupt, machine vulnerability.
- Thermal: burn damage over turns, explosive terrain, area denial.
- Cryogenic: slow, root/freeze, brittle targets take bonus damage.
- Nano: drones, repair, shields, deployable structures.
- Overload: AP conversion, critical windows, cooldown manipulation.

Examples:
- Hacker EMP + Engineer turret: turret gains a temporary chain-lightning shot.
- Cryo-marked enemy + Phantom precision strike: shatter bonus.
- Bastion blocks a corridor while Engineer controls the approach with mines.
- Thermal explosion ignites nearby volatile objects.

## Enemy intent system
Enemies announce planned actions during the player phase:
- Drone: move toward the nearest exposed operative and fire.
- Rusher: mark a target tile, then charge next enemy phase.
- Sniper: draw a targeting line; fire if the target remains in line of sight.
- Bulwark: guard adjacent enemies or advance to block a lane.
- Controller: create a hazard zone or buff nearby machines.
Intent must be visually distinct: move marker, attack line, danger tiles or shield icon. Player actions can interrupt, stun, push or block an intent.

## Room and run structure
1. Safehouse: select three operatives, equip gear and choose a starting contract.
2. Tactical encounter: fight on a grid with visible enemy intent.
3. Reward: choose one of three modules, gear pieces or resources.
4. Route map: choose combat, elite, supply, shop, event or boss.
5. Sector boss: multi-phase encounter with arena mechanics.
6. Extract or continue deeper.
7. Return to safehouse and spend retained resources on permanent unlocks.

Target expedition length: 25–45 minutes, to be validated through playtests.

## Progression
- During a run: modules, weapon modifications, consumables and temporary squad synergies.
- Between runs: operative unlocks, gear blueprints, safehouse services, codex entries and difficulty tiers.
- Defeat retains a portion of common resources; successful extraction retains the full haul.
- Higher difficulties add enemy behaviors and tactical modifiers, not merely inflated health.

## Scope targets
- 4 playable operatives; 3 deployed per encounter.
- 10+ weapon families and tactical modifications.
- 5 synergy families.
- 4 regions and 8+ bosses.
- Multiple difficulty tiers.
- Single-player only.

## Prototype acceptance criteria
- Grid selection and movement.
- Action point spending and End Turn.
- Range and line-of-sight validation.
- Enemy intent previews.
- Enemy phase resolution.
- At least three distinct operative abilities.
- Victory/defeat and a repeatable encounter loop.

## Explicitly out of scope for the reboot
Real-time movement, mouse-aim shooting, bullet-hell projectile dodging, real-time cooldown rotations and the old quick-switch action combat loop.
