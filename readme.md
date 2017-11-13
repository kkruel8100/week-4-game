# Star Wars RPG

## How the app works:

#### 1. When the game starts, the player will choose a character by clicking on the fighter's picture. The player will fight as that character for the rest of the game.

#### 2. The player must then defeat all of the remaining fighters. Enemies are moved to a different area of the screen. The player chooses an opponent by clicking on an enemy's picture.

#### 3. Once the player selects an opponent, that enemy is moved to a defender area. The player will now be able to click the attack button.

#### 4. Whenever the player clicks attack, their character damages the defender. The opponent will lose HP (health points). These points are displayed at the bottom of the defender's picture. The opponent character will instantly counter the attack. When that happens, the player's character will lose some of their HP. These points are shown at the bottom of the player character's picture.

#### 5. The player will keep hitting the attack button in an effort to defeat their opponent. When the defender's HP is reduced to zero or below, remove the enemy from the defender area. The player character can now choose a new opponent.

#### 6. The player wins the game by defeating all enemy characters. The player loses the game the game if their character's HP falls to zero or below.

## Game design notes:

#### 1. Each character in the game has 3 attributes: Health Points, Attack Power and Counter Attack Power.

#### 2. Each time the player attacks, their character's Attack Power increases by its base Attack Power. For example, if the base Attack Power is 6, each attack will increase the Attack Power by 6 (12, 18, 24, 30 and so on).

#### 3. The enemy character only has Counter Attack Power. Unlike the player's Attack Points, Counter Attack Power never changes.

#### 4. The Health Points, Attack Power and Counter Attack Power of each character must differ. No characters in the game can heal or recover Health Points. 

#### 5. A winning player must pick their characters wisely by first fighting an enemy with low Counter Attack Power. This will allow them to grind Attack Power and to take on enemies before they lose all of their Health Points. 

#### 6. A player can win and lose the game no matter what character they choose. The challenge comes from picking the right enemies, not choosing the strongest player.