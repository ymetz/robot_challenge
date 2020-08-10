# Real Robot Simulation: Bodensee Team

Cloned from: https://github.com/rr-learning/rrc_simulation

Remote repository is added as upstream branch.
Pull from Upstream branch via:
`git pull upstream master`

Install Instructions:
https://people.tuebingen.mpg.de/felixwidmaier/realrobotchallenge/simulation_phase/installation.html



Please use `git-lfs` (https://git-lfs.github.com/) to commit larger files, e.g. binaries, models etc.
Please use separate branches, if you make changes to the environment, via 
`git checkout -b <branch_name>`

and then merge changes back via:
```
git checkout master
git merge <branch_name>
```


### Original Readme

This repository is exclusively intended for participating
in the [simulation phase of the Real Robot Challenge](https://real-robot-challenge.com/simulation_phase).

For simulating the open-source version of the TriFinger robot, please use the 
repository linked on the official open-source [project website](https://sites.google.com/view/trifinger).


This repository contains a simulation, based on PyBullet, of the TriFinger robot
used in the Real Robot Challenge. In addition, it contains OpenAI gym
environments and evaluation scripts for the tasks of the simulation phase.

For more information on the challenge see:

- the [challenge website](https://real-robot-challenge.com)
- the [software
  documentation](https://people.tuebingen.mpg.de/felixwidmaier/realrobotchallenge/index.html)
  
  
## Authors
- Felix Widmaier
- Shruti Joshi
- Vaibhav Agrawal
- Manuel Wuethrich
