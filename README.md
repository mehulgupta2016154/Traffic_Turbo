## Pretrained environments

For playing around, weights for 2 environments have been trained till 2k episodes & stored in env_weights function. For trying, initialize the game_env object with '1' or 'final_v'

This repository utilizes Sweep, a tool that aids in the automation and management of machine learning experiments. It allows for efficient hyperparameter tuning, tracking of experiment metrics, and comparison of different experiment runs.

Read more on [Medium](https://medium.com/data-science-in-your-pocket/game-development-using-pygame-reinforcement-learning-with-example-f5b78c768610)




## The enviroment
![Capture](https://user-images.githubusercontent.com/31255225/154457530-fd36e042-6f3f-434a-84f4-f2f0374e7800.JPG)


The environment consists of the following elements

- Road :                 Reward = -3
- Boost :                Reward = 0
- Traffic Signal :       Reward = -20
- Car Jam :              Reward = -50
- House:                 Reward = 500

The end goal of the agent is to take up an optimal path so as to keep a high reward at the end of the episode. Any move is considered invalid if

1. Goes out of the enviroment
2. Any cell is already visited in a particular episode

## Setting up the environment

This has been done using Pygame library that provides GUI components & animation capabilities for python projects. 

## Training & Testing

The agent has been trained using Q Learning technique in Reinforcement learning for ~2.k episodes using random states as initialization point for each episode. 

## Pretrained environments

For playing around, weights for 2 environments have been trained till 2k episodes & stored in env_weights function. For trying, initialize the game_env object with '1' or 'final_v'

Read more on [Medium](https://medium.com/data-science-in-your-pocket/game-development-using-pygame-reinforcement-learning-with-example-f5b78c768610)


