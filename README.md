# navigation
Udacity DRLND First Project

Andrey Naumov


## Problem

An agent lives in a 3D environment.  It is restricted to move along the ground and within four walls, which form a square.  Scattered on the ground are yellow and blue bananas.

The agent senses the state of the environment along 37 dimensions which include a measurement of the agent's angular velocity and measurements of the distances to other objects in the environment along rays emanating from the agent [https://github.com/Unity-Technologies/ml-agents/issues/1134][https://github.com/Unity-Technologies/ml-agents/releases].

The agent may act on the environment in one of four ways: Walk forward, walk backward, turn left, or turn right.

The environment gives the agent a reward of +1 for collecting a yellow banana and -1 for collecting a blue banana.

An episode lasts for 300 time steps.

## Solution

The environment will be considered solved when, in the course of simultaneously learning and acting, the agent has received an average reward of (at least) +13 over 100 consecutive episodes.

## Running the code

Clone this repository:

`git clone https://github.com/drlndds/navigation.git`

Clone the DRLND project assignment code:

`git clone https://github.com/udacity/deep-reinforcement-learning.git`

Install the Unity environment code following the instructions in deep-reinforcement-learning/p1_navigation/README.md (copied here):

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the DRLND GitHub repository, in the `p1_navigation/` folder, and unzip (or decompress) the file. 


Next, copy navigation/Navigation.ipynb into deep-reinforcement-learning/p1_navigation/ and open it in Jupyter.

The notebook opens with the results of having run it.  You may recreate the results by re-running the entire notebook (selecting Restart & Run All from the Kernel menu).  This will include retraining the network -- which may take a while.





