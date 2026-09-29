# Dark Kingdom

A terminal-based text RPG adventure built with Python.

Choose your character, fight through the Dark Forest, upgrade your gear, and face the Dark King in a final showdown.

## Overview

Dark Kingdom is a turn-based RPG designed around character choice, combat strategy, exploration, and progression.

Players choose between three character classes, encounter enemies along a branching path, purchase upgrades from a merchant, and ultimately face a multi-stage final boss.

## Features

- **Three playable classes**
  - Warrior
  - Wizard
  - Rogue
- Unique character stats and special attacks
- Turn-based combat
- Regular and special attacks
- Special attack cooldowns
- Critical hits
- Health potions
- Random enemy encounters
- Branching exploration paths
- Castle Armory and Dungeon routes
- Merchant shop
- Weapons and character upgrades
- Multi-stage final boss battle
- Terminal-based game interface

## Character Classes

Each character offers a different approach to combat.

| Class | Play Style |
|---|---|
| **Warrior** | Strong physical attacks and durability |
| **Wizard** | Powerful special attacks |
| **Rogue** | Fast and critical-hit focused |

## Combat System

Combat takes place through turn-based encounters.

Players can choose between regular attacks, special attacks, and healing with potions.

Special attacks use cooldowns, requiring players to decide when to use their strongest abilities.

Randomized combat elements such as enemy behavior and critical hits help keep encounters unpredictable.

## Exploration

The game features a branching path through the castle.

Players encounter different challenges and can choose between areas such as:

- **Armory**
- **Dungeon**

Random enemy encounters can occur along the way, giving players opportunities to fight, earn rewards, and prepare for the final battle.

## Merchant

Between encounters, players can visit the Castle Merchant to purchase weapons and upgrades.

Managing resources and deciding when to upgrade becomes an important part of progressing toward the final boss.

## Final Battle

The adventure culminates in a multi-stage battle against the **Dark King**.

The final encounter combines the game's combat systems and progression mechanics into a larger challenge.

## Requirements

- Python 3.7+
- No external dependencies

The game uses only Python's standard library:

- `time`
- `random`

## How to Run

Clone the repository:

```bash
git clone https://github.com/Tjordanart/dark-kingdom.git
```

Navigate to the project directory:

```bash
cd dark-kingdom
```

Run the game:

```bash
python3 DarkKingdom.py
```

Follow the on-screen prompts to choose your character and make decisions throughout the adventure.

## Play the Game

A web version of Dark Kingdom is available here:

**[Play Dark Kingdom](https://www.tjordanart.com/dark-kingdom)**

## Terminal Compatibility

The game uses raw ANSI escape codes for colored terminal output.

Color support works best in terminals that support ANSI escape sequences, including most modern Linux, macOS, and Windows terminals.

If colors appear as garbled characters, try running the game in **Windows Terminal** or **WSL**.

## What I Practiced

This project provided practice with:

- Python programming
- Functions and reusable game systems
- Conditional logic
- Loops
- User input
- Randomization
- Game-state management
- Turn-based combat
- Character progression
- Branching game logic
- Terminal interfaces

## Author

**Tyler Jordan**

[GitHub](https://github.com/Tjordanart)  
[Portfolio](https://www.tjordanart.com)
