****************************************************************************************************************************************

## Assignment 2:

## Objective - Reinforcement Learning

•	The Frozen lake is a single player game in which the player has to navigate a 4 × 4 grid that consists of a starting point with the goal of arriving at the finish point on the grid from the starting position without falling in any of the death zones (also known as holes).Here, S is the starting point, G is the goal, F is the solid ice where the agent can stand and H is the hole where if the agent goes, it falls down. At each point on the grid, the player has the option to move around to any of the neighboring points.For every state F(ice), the agent gets 0 reward, for state H(hole) it gets -1 reward as in state H the agent will die and upon reaching the goal, the agent gets +1 reward. If the player moves to a hole, the player is killed and re-spawned at the starting point. The objective is to have an agent learn to navigate from the start to the goal without moving onto a hole and to maximize the score over time. At any given time the agent can choose to move either up, down, left, or right.The episode ends when the player either reaches the goal or falls in a hole. You receive a reward of 1 if you reach the goal, and zero otherwise.


