# Project: Navigation


## Introduction
In this project, the agent is trained to **navigate** in a large, square world to collect as much yellow bananas as possible while avoiding blue bananas. When a yellow banana is collected, a reward of 1 will be provided. On the contrary, a reward of -1 will be provided when a blue banana is collected.  

[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

![Trained Agent][image1]

## Project Details
The state space is 37 dimentions with agent's velocity and a ray-based perception of objects around agent's forward direction. The action space is discrete with 4 options:  

* 0 `--` move forward  
* 1 `--` move backward  
* 2 `--` turn left  
* 3 `--` turn right  

This task is considered as solved when an average score of +13 is gained over 100 consecutive episodes. The maximum allowed episode number is 1800.

## Getting Started  


1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the same folder with `navigation.ipynb` and unzip (or decompress) the file. 


3. You would need to use the Unity ML-Agents environment in this project. Make sure you have installed [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) and [NumPy](http://www.numpy.org/).

## Instructions


In the `navigation.ipynb`, when starting the Unity ML-Agetns environment, change the `file_name` parameter to the location of your Unity Environment with `UnityEnvironment(file_name = "your path")`.   

To train the agent, simply run `navigation.ipynb`. There is also a trained model saved in `model.pt`, which obtains the score of +13 within around 360 episodes. 




