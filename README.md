# ContinuousControl

### The Environment

The Unity Reacher environment is used for this project. A double-jointed arm can move to target locations, and a reward of +0.1 is received for each time step that the agent's hand is in the designated location. The goal of the agent is to maintain its position in the target location for as many time steps as possible, thus accruing the maximum reward.

There are 33 dimensions in the observation space corresponding to position, rotation, velocity, and angular velocities of the arm. Each action corresponds to torque applicable to two joints, and is therefore a vector with 4 numbers. Every entry in the action vector should be a number between -1 and 1.

In order to solve the environment, the agent must get an average score of 30 over 100 consecutive episodes. The task is episodic.

### Requirements

1. Download the environment from one of the links below.
 - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
 - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
 - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
 - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

2. Place the file in this GitHub repository, in the `ContinuousControl/` folder, and unzip (or decompress) the file. 
