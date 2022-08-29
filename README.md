# Example Random Shooting implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_random_shooting_example/blob/master/random_shooting_tutorial.ipynb) of random shooting with ReLAx.

Random Shooting actor was trained on HalfCheetah-v2 Mujoco Gym environment for 75k env-steps. 

The graph of average return vs training step is shown below (`batch_size=5000`):

![rs_training](https://github.com/nslyubaykin/relax_random_shooting_example/blob/master/rs_training.png)

The graph below shows actual rewards vs rewards fitted with environment model:

![rs_model_rews](https://github.com/nslyubaykin/relax_random_shooting_example/blob/master/rs_model_rews.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187182192-60a2d9fa-8961-4192-b321-57613abc0550.mp4
