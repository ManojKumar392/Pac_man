# Pacman Game

## Description

Pacman Game is a classic arcade game where players control Pacman, a hungry yellow circle, and navigate through a maze to eat all the dots while avoiding colorful ghosts. The objective is to clear each level by eating all the dots, and players can earn bonus points by eating power pellets that temporarily turn the ghosts blue, allowing Pacman to eat them for additional points.

### Pacman Rule

In Pacman Game, you control Pacman using the arrow keys or 'WASD' keys. The goal is to navigate through the maze and eat all the dots to clear the level. If Pacman collides with a ghost without consuming a power pellet, he loses a life. The game ends when all lives are lost, or when all levels are successfully cleared.

## How to Play

1. **Controls:**
   - Move Up: [Up Arrow] or 'W'
   - Move Down: [Down Arrow] or 'S'
   - Move Left: [Left Arrow] or 'A'
   - Move Right: [Right Arrow] or 'D'

2. **Objective:**
   - Eat all the dots to clear the level.
   - Eat power pellets to temporarily turn the ghosts blue and earn bonus points by eating them.

3. **Gameplay:**
   - Navigate Pacman through the maze using the arrow keys or 'WASD' keys.
   - Eat all the dots to clear the level.
   - Avoid ghosts; colliding with them without a power pellet costs a life.
   - Eating a power pellet will turn the ghosts blue and allow Pacman to eat them for bonus points.

## Ghost Modes

Ghosts in Pacman Game exhibit different behavior patterns:

1. **Chase Mode:**
   - Ghosts actively pursue Pacman and try to predict his movements.

2. **Scatter Mode:**
   - Ghosts move to predefined corners of the maze.

3. **Frightened Mode:**
   - When Pacman eats a power pellet, the ghosts turn blue and become vulnerable.
   - In Frightened Mode, ghosts will run away from Pacman, providing an opportunity for him to eat them.

4. **Respawn:**
   - After being eaten, ghosts respawn in their starting positions.

## Ghost behavior

1) Red Ghost a.k.a Blinky : This little fella is aggressive . He targets you and comes at you . Brawn isnt always the smart way though and this boi is easy to avoid.

2) Pink Ghost a.k.a Pinky : Unlike its name , this ghost aint dumb. She(pink) calculates the tiles a fair bit in front of you and target that . Her plan is to get you from front. Along with Blinky , they make the ever popular brain and brawn combination.

3) Cyan Ghost a.k.a Inky : This thing is hard to understand . So I would just like to tell you to be CAREFUL. And now for the nerds, He extends your direction up front joins it with Blinky to make a vector and adds it to your direction and targets that making him erractic

4) Orange Ghost a.k.a Clyde : Couldnt find the reason for his naming but he is a wimp like me. He acts similar to Blinky when far but when he is near he runs away 

## Installation

To play Pacman Game, follow these steps:

1. Clone this repository to your local machine.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run the game using the following command:

```bash
python pacman_game.py
```


alternatively , you can run the .exe file
