# DDPGforRoboticsControl
This is an implementation of Deep Reinforcement Learning algorithm named Deep determinsitic Policy Gradient (DDPG) to train a 4 DOF robotic Arm to reach the moving target. The action space is continous and the learned agent outputs the torque for the robot to move to the specific target location.

![](DeepReinforcementLearning.gif)

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.


###Environment
A Unity Environment containing 20 identical agents, each with its own copy of the environment.

###Solving the Environment

Your agents must get an average score of +30 (over 100 consecutive episodes, and over all agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 20 (potentially different) scores. We then take the average of these 20 scores.
This yields an average score for each episode (where the average is over all 20 agents). The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.

