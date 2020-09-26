---
title: "Projects and Open Source Software"
excerpt: "Links to open-source machine learning and robotics software repositories developed as part of research projects"
layout: archive
permalink: /projects/
author_profile: true
toc: true
toc_label: "Projects"
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.75"
  overlay_image: /images/vancouver_crop.jpg
  caption: "Vancouver, Canada"
---

# Undergraduate Final Year Thesis
---
## [Humanoid Maze Solver using Deep Reinforcement Learning](https://github.com/arpit-kapoor/RL-Humanoid)
![demo](/images/humanoid-final-crop.gif){: .align-right .width-half}
Hierarchical Deep Reinforcement learning inspired approach used to teach a higher order complex task (solving a maze) to a humanoid. The approach consists of two policies; a higher level maze solver policy and a lower level Humanoid mobility policy. The code base is developed using Mujoco and Roboschool, while the policy is trained in Tensorflow.

<br>

<br>

# Bayesian Machine Learning
---
Various implementations of Markov Chain Monte Carlo Schemes for training Bayesian Neural Networks and other machine learning models.

**[Bayesian Neural Transfer Learning](https://github.com/sydney-machine-learning/Bayesian-neural-transfer-learning)** <br>
A Transfer Learning methodogy for Bayesian Neural Networks via MCMC <br>
[Link to Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231219314213)

**[Surrogate-assisted Parallel Tempering for Bayesian Neural Networks](https://github.com/sydney-machine-learning/surrogate-assisted-parallel-tempering)** <br>
Surrogate assisted multi-core parallel tempering for optimized training of Bayesian Neural Networks <br>
[Link to Paper](https://www.sciencedirect.com/science/article/abs/pii/S0952197620301299)

**[Parallel Tempering for Bayesian Neuroevolution](https://github.com/sydney-machine-learning/evolutionary-pt)**<br>
Multi-core implementation of Population based Bayesian neuroevolution 

**[Multi-core Parallel Tempering Bayeslands](https://github.com/intelligentEarth/pt-Bayeslands)**<br>
Parallel Tempering via MCMC for Badlands Geoscientific model

**[Surrogate-assisted Bayeslands](https://github.com/intelligentEarth/surrogate-pt-Bayeslands)**<br>
Surrogate version of BayesLands to reduce runtime <br>
[Link to Paper](https://gmd.copernicus.org/articles/13/2959/2020/gmd-13-2959-2020.html)


<br>

# Robotics
---
**[Pynamixel](https://github.com/SRM-Team-Humanoid/pynamixel)** <br>
Python module written on top of DynamixelSDK to provide convinient interface with [Robotis Dynamixel Smart Robotic Actuators](http://www.robotis.us/dynamixel/)

**[ROS Dynamixel](https://github.com/SRM-Team-Humanoid/ros_dynamixel)** <br>
Robot Operating System (ROS) package that provides a ROS Message interface to interact with Dynamixel Actuators.