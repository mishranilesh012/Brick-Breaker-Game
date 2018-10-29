# Brick-Breaker-Game
The project implemented consists of a game in which the player smashes a wall of bricks by deflecting the bouncing ball with a paddle. The paddle will only move in a horizontal way and will be controlled by the player with the left and right arrows of the keyboard or with the mousse. The player will win this game after destroying all the bricks in the level. Similarly, the player will lose if he fails to catch the ball with the paddle 3 times.

Rules

•	Initial X and Y velocities are 100 units per second.
•	When a ball hits a wall, negate the X velocity
•	When a ball hits the left side of a block, negate the Y velocity, and decrease the X velocity by a constant amount
•	When a ball hits the right side of a block, negate the Y velocity, and increase the X velocity by a constant amount
•	When a ball hits the middle of a block or the ceiling, negate the Y velocity
