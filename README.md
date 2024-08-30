# Reinforcement Learning: Grid World Environment Exploration

## Introduction

This project is a simple implementation of a grid world environment for reinforcement learning exploration. This is from [UC Berkeley's CS188 Reinforcement Learning Project](http://ai.berkeley.edu/reinforcement.html). The goal of this assignment is to update `qlearningAgents.py` and `valueIterationAgents.py` to work with the grid world environment.


## Grid World Environment

The grid world environment is a 2D grid where the agent can move in four directions: up, down, left, and right. The agent can move to a new cell in the grid if it is not blocked by a wall. The agent receives a reward of -1 for each step it takes. The goal of the agent is to reach the terminal state, which is the cell with the highest reward. The agent can also receive a reward of -100 if it tries to move into a wall. The agent can also receive a reward of -10 if it tries to move out of the grid. The agent can also receive a reward of -1 if it tries to move into a cell that is already occupied by another agent.