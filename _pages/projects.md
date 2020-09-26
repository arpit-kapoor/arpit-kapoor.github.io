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

feature_row:
  - image_path: /images/projects/teleop.gif
    alt: "Humanoid Teleoperation"
    title: Humanoid Teleoperation
    excerpt: This project involves a Kinect 360 motion sensor to capture human motions and imitation by the humanoid robot with legged motion
    url: https://ieeexplore.ieee.org/document/8610719
    btn_label: "Paper"
    btn_class: "btn--success"
  - image_path: /images/projects/picaso.gif
    title: Gesture controlled Robotic Arm
    alt: "Gesture controlled Robotic Arm"
    excerpt: A robot arm with 6 degrees of freedoms and can be controlled with gestures!

---

# Undergraduate Final Year Thesis
---
![demo](/images/projects/humanoid-final-crop.gif){: .align-right .width-half}
**[Humanoid Maze Solver using Deep Reinforcement Learning](https://github.com/arpit-kapoor/RL-Humanoid)** <br>
Hierarchical Deep Reinforcement learning inspired approach used to teach a higher order complex task (solving a maze) to a humanoid. The approach consists of two policies; a higher level maze solver policy and a lower level Humanoid mobility policy. The code base is developed using Mujoco and Roboschool, while the policy is trained in Tensorflow.

[Project](https://github.com/arpit-kapoor/RL-Humanoid){: .btn .btn--primary}

<br>


# Bayesian Machine Learning
---
Various implementations of Markov Chain Monte Carlo Schemes for training Bayesian Neural Networks and other machine learning models.

**Bayesian Neural Transfer Learning** <br>
A Transfer Learning methodogy for Bayesian Neural Networks via MCMC <br>
[Code](https://github.com/sydney-machine-learning/Bayesian-neural-transfer-learning){: .btn .btn--primary} [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231219314213){: .btn .btn--success}

**Surrogate-assisted Parallel Tempering for Bayesian Neural Networks** <br>
Surrogate assisted multi-core parallel tempering for optimized training of Bayesian Neural Networks <br>
[Code](https://github.com/sydney-machine-learning/surrogate-assisted-parallel-tempering){: .btn .btn--primary} [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0952197620301299){: .btn .btn--success}

**Parallel Tempering for Bayesian Neuroevolution**<br>
Multi-core implementation of Population based Bayesian neuroevolution <br>
[Code](https://github.com/sydney-machine-learning/evolutionary-pt){: .btn .btn--primary}

**Multi-core Parallel Tempering Bayeslands**<br>
Parallel Tempering via MCMC for Badlands Geoscientific model <br>
[Code](https://github.com/intelligentEarth/pt-Bayeslands){: .btn .btn--primary}

**Surrogate-assisted Bayeslands**<br>
Surrogate version of BayesLands to reduce runtime <br>
[Code](https://github.com/intelligentEarth/surrogate-pt-Bayeslands){: .btn .btn--primary} [Paper](https://gmd.copernicus.org/articles/13/2959/2020/gmd-13-2959-2020.html){: .btn .btn--success}


<br>

# Robotics
---

{% include feature_row%}


**Pynamixel** <br>
Python module written on top of DynamixelSDK to provide convinient interface with [Robotis Dynamixel Smart Robotic Actuators](http://www.robotis.us/dynamixel/) <br>
[Code](https://github.com/SRM-Team-Humanoid/pynamixel){: .btn .btn--primary}

**ROS Dynamixel** <br>
Robot Operating System (ROS) package that provides a ROS Message interface to interact with Dynamixel Actuators <br>
[Code](https://github.com/SRM-Team-Humanoid/ros_dynamixel){: .btn .btn--primary}