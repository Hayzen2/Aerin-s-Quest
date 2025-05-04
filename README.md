# Aerin's Quest

## Gameplay Overview
**Aerin's Quest** is a fast-paced 2D adventure game where players control an archer named **Aerin**, who must traverse dangerous terrain, climb towering obstacles, and fend off different kinds of enemies using a bow. The game blends platforming elements, dynamic combat, and environmental hazards that test both timing and strategy. As players explore, they’ll encounter tricky climbing sections, spikes, and enemies that require jumping over or using different strategies to get by.

## Genre
- Single-player 2D Adventure Platformer

## Storyline
In **Aerin’s Quest**, you play as **Aerin**, the last protector of your land, which has been overrun by dangerous creatures. These enemies have stolen vital treasures that keep your kingdom safe and peaceful. Without them, chaos has spread everywhere.

Your mission is to travel through perilous places, defeat enemies, and collect the lost treasures. Each treasure you recover weakens the invaders and helps restore peace to your home. If you retrieve enough treasures, your land will be freed, and peace will return to your people.

## Visual Style
- Hand-drawn 2D pixel art with animation for:
  - Running
  - Idling
  - Shooting
  - Climbing
  - 
## State-driven Cameras

- **Idling**: 
  - If the character remains idle for 5 seconds, the camera will slowly zoom in on the character.

- **Shooting or Moving**: 
  - When the character shoots or moves, the camera will instantly zoom out to provide a better view of the environment.

- **Climbing**: 
  - When the character starts climbing, the camera will instantly zoom in on the character.

## Gameplay Mechanics

### Interaction and Solo Play
- The game is **single-player** focused, allowing players to explore at their own pace and tackle challenges in various ways.

### Controls

- **ESC**: Open menu settings.
- **Main Menu**: Return to the main menu screen.
- **Quit Game**: Quit the game and automatically save progress.
- **P**: Pause the game (press again to resume).

#### Movement Controls:
- **Running**: Automatic
- **Jump**: Spacebar
- **Move Left**: 'A' or Left Arrow key
- **Move Right**: 'D' or Right Arrow key
- **Climb Ladders**: Hold Up/Down Arrow key or 'W'/'S' keys

#### Combat with Bow:
- **Hold Bow**: Shift
- **Enter Aiming Mode**: X
- **Shoot**: Release X (Arrows are generated and shoot in the direction you're facing)

#### Collecting Coins and Treasure Chests:
- **Coins**: Run through them to automatically collect.
- **Treasure Chests**: Run through them to automatically open.

### Health and Damage System

- **Starting Health**: 100 HP (can be reduced by enemies and environmental hazards).
  
#### Health States:
- **Full HP**: 100 HP
- **Average HP**: 40–60 HP
- **Low HP**: 40 HP or less

#### HUD:
- Displays the player’s health, updating in real-time. If health reaches zero, the player dies immediately.
- Displays status effects like poison or slowed state.

#### Environmental Dangers:
- **Spikes**: Touching spikes results in instant death. Be cautious while navigating hazardous areas.

#### Enemies:
- **Red Enemies**: Touching them causes 5 damage points.
- **Green Enemies**: Touching them slowly drains health (2 points every 2 seconds) until the player finds a potion to cure it.
- **Blue Enemies**: Touching them slows the player down for a period.

#### Potions:
- **Red Potion**: Heals 50 health points (half of health bar).
- **Green Potion**: Cures the poisoned state caused by green enemies.

### Climbing and Navigation:
- **Climbing Ladders**: Use up or down arrow keys ('W'/'S') to climb ladders.
- **Jumping on Bouncy Mushrooms**: Use these to navigate to higher platforms.

### Going Through Each Level

- **Advancing to the Next Level**: 
  - The player can only progress to the next level once they have opened the treasure chest of the current level.
  - Moving to the corner of the other side of the level will automatically trigger the transition to the next level.

- **Death and Restart**: 
  - If the player dies, all progress is reset, and they will be sent back to the start screen to begin again.

## Copyright and Credits

**Font:**
- The font used in the game is called **Karmatic Arcade**, which is available for both personal and commercial use. You can find it at the following source:  
  [Karmatic Arcade Font - Free for Personal & Commercial Use](https://www.fontsc.com/font/karmatic-arcade)

**Sound Effects:**
- The following sound effects are used in the game, sourced from free online platforms:

  - **Coin Pickup**: [Coin Received - Pixabay](https://pixabay.com/vi/sound-effects/coin-recieved-230517/)
  - **Bow Loading**: [Bow Loading - Pixabay](https://pixabay.com/vi/sound-effects/bow-loading-38752/)
  - **Arrow Shooting**: [Bow and Arrow Sound Effect - Pixabay](https://pixabay.com/vi/sound-effects/bow-and-arrow-shootsound-effect-1-239700/)
  - **Game Start**: [Game Start - Pixabay](https://pixabay.com/sound-effects/game-start-6104/)
  - **Enter New Level**: [New Level - Pixabay](https://pixabay.com/vi/sound-effects/new-level-142995/)
  - **Game Over**: [Game Over Arcade - Pixabay](https://pixabay.com/vi/sound-effects/game-over-arcade-6435/)
  - **Mushroom Bounce**: [Retro Jump - Pixabay](https://pixabay.com/vi/sound-effects/retro-jump-3-236683/)
  - **Drink Potion**: [Glug Glug Glug - Pixabay](https://pixabay.com/vi/sound-effects/glug-glug-glug-39140/)
  - **Climb Ladders**: [Ladder - Pixabay](https://pixabay.com/vi/sound-effects/ladder-82581/)
  - **Opening Chests**: [90s Game UI - Pixabay](https://pixabay.com/vi/sound-effects/90s-game-ui-6-185099/)
  - **Game Win**: [8-Bit Victory Sound - Pixabay](https://pixabay.com/vi/sound-effects/8-bit-victory-sound-101319/)
 
## Short Demo Video: ##

[![Aerin's Quest DEMO](https://img.youtube.com/vi/FjojeRYXjcQ/maxresdefault.jpg)](https://youtu.be/FjojeRYXjcQ)  
*Click to watch the short demo of my first game project.*
