This is a simple 3D game where the player must complete different objectives to escape. The game has three areas, each with its own challenges.

### Area 1 — Collecting Energy Cores

The player starts in the first area and meets an NPC who asks them to collect three energy cores.

- Collect three energy cores to increase the score.
- Press E to interact with the NPC.
- The NPC gives different dialogue depending on whether the quest is completed.
- After collecting all three energy cores, the player can unlock the door to the next area.

### Area 2 — Enemy Combat

The second area introduces combat and enemy AI.

- The enemy patrols between two waypoints.
- The enemy detects and chases the player when they enter its vision range.
- The enemy attacks the player when close enough.
- The player can shoot the enemy using a line trace.
- Both the player and enemy have health systems and health bars.
- The player has limited ammunition and can collect ammo pickups.

### Area 3 — Sacrifice

The final area focuses on the game's theme, Sacrifices Must Be Made.

- The area contains a dangerous trap that damages the player.
- The player can interact with a sacrifice altar.
- Using the altar sacrifices 30 HP.
- The sacrifice disables the trap and unlocks the final exit.
- The player can then escape and complete the game.

## Implemented Features

- Three playable areas
- Collectible items and score system
- NPC interaction and quest system
- Doors that open using Timeline animations
- Level transitions
- Player health and health bar
- Enemy health and health bar
- Shooting using line traces
- Limited ammunition and ammo pickups
- Enemy patrol and chase AI
- Enemy detection using Pawn Sensing
- Enemy attacks and player damage
- Sacrifice altar and damage traps
- GameInstance for keeping player data between levels
- Main menu and ending screens
- Restart and quit options
- Different endings for player death and successful escape

## Additional Features

**NPC Quest System:** The NPC gives the player an objective and responds differently after the player completes it.

**Sacrifice Mechanic:** The player must give up part of their health to disable a dangerous trap and reach the final exit.
