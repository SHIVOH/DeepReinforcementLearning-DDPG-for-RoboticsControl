# DDPGforRoboticsControl
This is an implementation of Deep Reinforcement Learning algorithm named Deep determinsitic Policy Gradient (DDPG) to train a 4 DOF robotic Arm to reach the moving target. The action space is continous and the learned agent outputs the torque for the robot to move to the specific target location.

![](DeepReinforcementLearning.gif)

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.
