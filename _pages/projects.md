---
# title: "Projects and Open-source Software"
# excerpt: Links to open-source machine learning and robotics software repositories developed as part of research projects
layout: splash
permalink: /projects/
author_profile: false
# toc_label: "Projects"
# classes: wide
# header:
#   overlay_color: "#000"
#   overlay_filter: "0.75"
#   overlay_image: /images/awards/IROS17_2.jpg
#   caption: "IROS 2017, Vancouver, Canada"

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

  - image_path: /images/projects/balance.gif
    title: Self Balancing Humanoid
    alt: "Dynamic Lateral balance"
    excerpt: Humanoid capable of self balancing on unstable surfaces like a suspension bridge
    url: https://ieeexplore.ieee.org/abstract/document/8284564
    btn_label: "Paper"
    btn_class: "btn--success"


---
<p style="text-align: center; font-size:42px;"> Projects </p>

---
<p style="text-align: center; font-size:24px;"> <b> Undergraduate Final Year Thesis </b> </p> 

**Humanoid Maze Solver using Deep Reinforcement Learning** <br>
A Deep Reinforcement learning inspired approach used to teach a higher order complex task (solving a maze) to a humanoid. The approach consists of two policies; a higher level maze solver policy and a lower level Humanoid mobility policy. The simulation was generated in a MuJoCo environment, while the policy is trained using Tensorflow.

[Project](https://github.com/arpit-kapoor/RL-Humanoid){: .btn .btn--primary}

![demo](/images/projects/humanoid-final-crop.gif){:.align-center .width-quarter}

<br>

---
<p style="text-align: center; font-size:24px;"> <b>Humanoid Robotics</b> </p> 

{% include feature_row%}

<br>

<p style="text-align: center; font-size:24px;"> <b>Bayesian Machine Learning</b> </p> 
Various implementations of Markov Chain Monte Carlo Schemes for training Bayesian Neural Networks and other machine learning models.

**Parallel Tempering for Bayesian Neuroevolution**<br>
The proven effectiveness of neuroevolution in Deep Learning ([here](https://eng.uber.com/deep-neuroevolution/)) is the motivation behind this project. This project investigates the effectiveness of multi-core implementation of parallel MCMC for population based Bayesian neuroevolution in pattern classification and time series problems.<br>
[Code](https://github.com/sydney-machine-learning/evolutionary-pt){: .btn .btn--primary}

**Bayesian Neural Transfer Learning** <br>
Quantify uncertainity in Tranfer Learning with Bayesian Neural Networks trained via Markov Chain Monte Carlo <br>
[Code](https://github.com/sydney-machine-learning/Bayesian-neural-transfer-learning){: .btn .btn--primary} [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231219314213){: .btn .btn--success}

**Surrogate-assisted Parallel Tempering for Bayesian Neural Networks** <br>
We use surrogate model to estimate the computationally expensive objective functions in Parallel Tempering to reduce the overall runtime of the MCMC sampling on large problems.<br>
[Code](https://github.com/sydney-machine-learning/surrogate-assisted-parallel-tempering){: .btn .btn--primary} [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0952197620301299){: .btn .btn--success}

**Surrogate-assisted Bayeslands**<br>
Surrogate version of BayesLands which is a Bayesian framework for [Badlands](https://github.com/badlands-model/badlands).<br>
[Code](https://github.com/intelligentEarth/surrogate-pt-Bayeslands){: .btn .btn--primary} [Paper](https://gmd.copernicus.org/articles/13/2959/2020/gmd-13-2959-2020.html){: .btn .btn--success}

<br>

<br>

---
<p style="text-align: center; font-size:24px;"> <b> Software Packages </b></p> 
**Pynamixel** <br>
Python module written on top of DynamixelSDK to provide convinient interface with [Robotis Dynamixel Smart Robotic Actuators](http://www.robotis.us/dynamixel/) <br>
[Code](https://github.com/SRM-Team-Humanoid/pynamixel){: .btn .btn--primary}

**ROS Dynamixel** <br>
Robot Operating System (ROS) package that provides a ROS Message interface to interact with Dynamixel Actuators <br>
[Code](https://github.com/SRM-Team-Humanoid/ros_dynamixel){: .btn .btn--primary}

<br>