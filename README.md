# Traffic Turbo 🏍️

Traffic Turbo is a road based environment where the agent (top left corner) is trained to reach his home (bottom right corner). The training & Testing for one of the random environments can be seen [here](https://www.youtube.com/watch?v=TfjtjKFSpmE)


## The enviroment
![Capture](https://user-images.githubusercontent.com/31255225/154457530-fd36e042-6f3f-434a-84f4-f2f0374e7800.JPG)

The environment consists of the following elements

- Road : Reward = -3
- Boost : Reward = 0
- Traffic Signal : -20
- Car Jam : -50
- House: 500

The end goal of the agent is to take up an optimal path so as to keep a high reward at the end of the episode. Any move is considered invalid if

1. Goes out of the enviroment
2. Any cell is already visited in a particular episode

## Setting up the environment

This has been done using Pygame library that provides GUI components & animation capabilities for python projects. 

## Training & Testing

The agent has been trained using Q Learning technique in Reinforcement learning for ~2.k episodes using random states as initialization point for each episode. 

## Pretrained enviromnets

For playing around, weights for 2 environments have been trained till 2k episodes & stored in env_weights function. For trying, initialize the game_env object with '1' or 'final_v'


