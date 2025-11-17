# Shadow-Dungeon---Part-1
ShadowDungeon -- Part 1
The project uses an object-oriented approach with classes representing the player and rooms.
ShadowDungeon : The main class that extends AbstractGame. Handles the game loop, player movement, room transitions, rendering, and input handling. It also tracks game state and player stats.
Character: Represents the player character, storing position, health, coins, and images for left/right movement.
SimpleRoom: Represents non-battle rooms, primarily for the Prep Room and End Room. Handles door state and position.
BattleRoom: Represents rooms with obstacles, enemies, and treasures. Tracks doors, treasures collected, and obstacles such as walls or rivers.
