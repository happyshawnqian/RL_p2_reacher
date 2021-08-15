
[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"

# Project Details
In this project, reinforcemnt learning (Deep Deterministic Policy Gradient) is used to control two-jointed arms to reach moving targets.

![Trained Agent][image1]

In the environment, each double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

# Getting Started
The official instructions for installing the unity environment and dependencies can be found [here](https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control).

# Instructions
Run the jupyter notebook file `Continuous_Control_DDPG_v2.ipynb` in the repository for training the agent and see the result.