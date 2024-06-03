# dream-game

Game title : DreamGame.

Setting :The game is set in a labyrinth world with a dark atmosphere. Imagine being Pac-Man but as a human running through a maze of twisting corridors  and being chased by horrific cube-like monster.
Concept: Endable runner-like game where players control a character who must avoid obstacles and escape from constant chaser.

Goal: The primary goal of the game is to get to the finish line avoiding obstacles and not getting caught by the enemy. Secondary goals include collecting pick-ups to achieve high speed and compete on leaderboards.

Core mechanics: 
- Movement: The main character (runner) moves forward. The player controls the character's ability to jump and crouch to avoid obstacles.
- Jump: The character can jump to avoid obstacles or collect items in the air. The jump height and duration are controlled by a single input or double input to perform second jump in the air.
- Crouch: The character can crouch to slide under obstacles.
- Chasing Mechanic: An enemy character is constantly chasing the player. The game ends if the enemy catches the runner.
- Obstacle Interaction: The player must navigate around obstacles by jumping or crouching. Colliding with some obstacles slows the runner down, allowing the enemy to catch up and another obstacles can deal certain amount of damage causing death.
- Item Collection: The player can collect items (pick-ups) while running. These items can provide temporary boosts or bonuses.

Actors and Components:
 Main Character  - Runner. The runner is a dynamic and agile character, designed for fast-paced movement through a labyrinth environment. 
 Abilities : 
 
   - Run. The runner's forward / side  movement is controlled by the player. The player can control the direction of the runner. 
   - Jump.  The runner can perform a high jump to avoid high obstacles and reach elevated items.
   - Double jump. The runner can perform a second jump while in mid-air.
   - Crouching. The runner can crouch to pass under low obstacles.

Attributes :
  -  Speed. The runner's speed is influenced by various actions and conditions. The runner can accelerate to a maximum speed if they constantly run for atleast 2 seconds. The runner's speed can be reduced by certain actions or obstacles like crouching or collisions with terrain. 
  -  Health. Displayed on the screen. The runner has a health meter that decreases when colliding with certain obstacles. Health can be restored by collecting health pick-ups.

Enemy ( Chaser ). 
-  Chase. The chaser continuously follows the runner, maintaining a consistent speed, non-collidable.
  Attributes:
- Invulnerability. Cannot be killed or damaged, so that has no health.
- Constant speed.  Has unchangable speed all the time.

Obstacles. Various obstacles such as barriers, low tunnels, and high walls. These are designed to challenge the player's reflexes and timing.
Interaction: The runner must jump over, double jump over, or crouch under these obstacles. Collisions slow the runner down. 

Pick-ups.

Health Rune:
Description: Restores a portion of the runner's health when collected.
Interaction: The player collects these by running into them.
Speed Rune:
Description: Temporarily increases the runner's speed when collected.
Interaction: The player collects these by running into them.

Dynamic obstacles  (traps ). 
Moving Saw:
Description: A spinning saw that moves along a predefined path, creating a timing challenge for the player.



