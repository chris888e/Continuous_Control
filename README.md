# Continuous Control

This repository contains a solution for the Unity "Reacher" environment. For this environment, the objective is to control a double-jointed "reacher" arm so that it follows a target location. There are two versions of the environment. One of these has just a single copy of the reacher arm "agent", the other version has 20 agents, all operating simultaneously. This solution solves the 20 agent version. 


The code trains the agents using an algorithm known as Deep Deterministic Policy Gradients (DDPG). This is an "actor-critic" algorithm that employs two neural networks, one for the actor, the other for the critic. The environment is considered solved when a score of at least 30, averaged over 100 episodes, is achieved.  


## Dependencies

Set up a python environment and download the Unity environment by following steps 1 and 2 of the instructions <a href="https://classroom.udacity.com/nanodegrees/nd893/parts/286e7d2c-e00c-4146-a5f2-a490e0f23eda/modules/089d6d51-cae8-4d4b-84c6-9bbe58b8b869/lessons/5b822b1d-5c89-4fd5-9b52-a02ddcfd3385/concepts/2303cf3b-d5dc-42b0-8d15-e379fa76c6d5">here</a>.

## Installation

To run the DQN solution code, download the following files and place them in the same directory:
    
    Continuous_Control.ipynb
    dqn_agent.py
    model.py

The code can then be run by opening the Continuous_Control notebook in the prescribed environment and running the cells.

