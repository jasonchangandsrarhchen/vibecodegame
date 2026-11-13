# NEON ABYSS PROTOCOL — Game Design Document
Version 0.1 · Prototype baseline

## High concept
A single-player, top-down action roguelite set in a neon-drenched underground megacity controlled by a corrupted AI called NEXUS. The player is an augmented operative entering sealed sectors to recover data and uncover the cause of the collapse.

**Design pillars**
1. Immediate, responsive combat with manual mouse aiming.
2. Build freedom: character identity shapes playstyle but does not lock weapon or upgrade choices.
3. Tactical pacing: quick standard encounters, deliberate elite and boss fights.
4. Meaningful risk: choose routes, decide when to extract, and retain part of resources after defeat.
5. Replayability through random upgrades, weapon combinations and persistent unlocks.

## Camera, controls and combat
- Fixed top-down camera.
- WASD movement, mouse aim/fire, 1/2 weapon switch, Space dash, E/right-click operative skill, Q ultimate, Esc pause.
- One primary and one secondary weapon.
- Dash grants a short invulnerability window and has a cooldown.
- Combat feedback uses hit flashes, particles, projectile colors, screen shake and synthesized audio cues.

## Operatives
| Operative | Role | Passive identity | Active skill |
|---|---|---|---|
| Phantom / 幽影 | Mobility and precision | Consecutive kills build focus | Phase dash |
| Bastion / 堡壘 | Defense and frontline | Periodic shield recovery | Bastion barrier |
| Engineer / 工程師 | Deployables | Improved turret uptime | Auto-turret |
| Hacker / 駭客 | Crowd control | Improved disruption duration | System shutdown |

Operatives should encourage distinct builds without restricting access to weapons or general upgrades.

## Weapons
| Weapon | Identity |
|---|---|
| Arc Pistol | Accurate energy sidearm; chain effects |
| Plasma Shotgun | Close-range multi-projectile burst |
| Pulse Rifle | High rate of fire and stable tracking |
| Rail Lance | Slow, high-damage piercing shot |

The intended full-game roster is 10+ weapons. Prototype weapons are deliberately limited to validate the two-slot combat loop first.

## Upgrade families and synergies
- Electromagnetic: chain lightning, stun and EMP.
- Thermal: burn, explosions and heat.
- Cryogenic: slow, freeze and shatter.
- Nano: drones, repair and persistent summons.
- Overload: critical hits, attack speed and burst windows.

Prototype upgrades include damage, fire rate, critical chance, chain lightning, burn, freeze, drones, lifesteal, dash burst, nova explosions and shields.

## Run structure
1. Start from safehouse and select an operative.
2. Enter a sector and clear rooms.
3. Choose a branching route: combat, supply, elite, shop or anomaly.
4. Every fourth cleared room offers a sector boss encounter.
5. Defeat the boss to advance to the next sector.
6. Extract when desired or continue deeper.
7. Spend retained scrap on permanent safehouse upgrades.

Target full-run length: approximately 25–45 minutes, subject to playtesting.

## Room types
- Combat: standard enemy waves and reliable XP/scrap.
- Elite: tougher composition and improved rewards.
- Boss: named encounter with radial projectile patterns.
- Supply: healing and a modest resource cache.
- Shop: trade scrap for healing or temporary damage.
- Anomaly: choose between a risky power boost and a safe resource reward.

## Enemies
- Drone: basic pursuit unit.
- Rusher: fast melee pressure.
- Sniper: maintains distance and fires aimed projectiles.
- Tank: slow, high-health threat.
- Boss: large health pool and radial bullet patterns.

Future enemy roles: shield bearer, repair drone, summoner, area-denial artillery and kamikaze unit.

## Progression and economy
- Run XP grants a level-up; choose one of three random upgrades.
- Scrap is the run currency.
- Successful extraction retains all run scrap; defeat retains 45%.
- Permanent safehouse upgrades improve starting hull, weapon damage and resource recovery.
- Higher difficulty tiers unlock after clears in the full design; the prototype currently focuses on the baseline loop.

## Visual direction
- Neon sci-fi / cyberpunk industrial spaces.
- Dark navy environment, cyan player silhouette, pink/red hostile signals, amber elite/boss accents.
- Geometric silhouettes and strong projectile contrast take priority over decorative detail.

## Scope targets for the full game
- 4 playable operatives.
- 10+ weapons and meaningful weapon modifiers.
- 5 upgrade/synergy families.
- 4 major regions and 8+ bosses.
- Progressive difficulty tiers with mechanical modifiers, not just inflated enemy health.

## Current prototype limitations
- Single HTML file; no asset pipeline or bundler.
- Keyboard/mouse only; touch and gamepad are not implemented.
- Audio is synthesized and intentionally minimal.
- Boss patterns, enemy AI, balance and room generation are early placeholders.
- Local browser save only; no cloud save or account system.
