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

3.	Set up the Python environment:

    a.	Create and activate a new environment with Python 3.6.
    - Linux or Mac:
        ```
        conda create –name drlnd python=3.6
        source activate drlnd
        ```
    - Windows:
        ```
        conda create –name drlnd python=3.6
        activate drlnd
        ```
    b.	Do a minimal install of OpenAI gym using
    
        pip install gym
    c.	Install the classic control & box2d environments using
    
        pip install Box2D
        pip install gym[all]
        pip install piglet==1.2.4
        pip install gym[box2d]
    d.	Clone the repository, navigate to the python folder, and install dependencies using
    ```
    git clone https://github.com/udacity/deep-reinforcement-learning.git
    cd deep-reinforcement-learning/python
    pip install .
    ```
    e.	Create an IPython kernel for the drlnd environment.
    
        python –m ipykernel install –user –name drlnd –display-name “drlnd”
    f.	Before running the code in the notebook, change the kernel to the “drlnd” kernel that you just created by using the drop-down Kernel menu.
    
    g. In order to train the agent, run the code cells sequentially.
