---
# title: "Projects and Open-source Software"
# excerpt: Links to open-source machine learning and robotics software repositories developed as part of research projects
layout: archive
permalink: /projects/
author_profile: true
title: "Projects"
# classes: wide
header:
  overlay_color: "#111"
  overlay_filter: "0.5"
  overlay_image: /images/header/cradle.jpg
  caption: "Cradle Mountain, Tasmania, Australia"

feature_row:

  - image_path: /images/projects/teleop.gif
    alt: "Humanoid Teleoperation"
    title: Humanoid Teleoperation
    excerpt: This project involves a Kinect 360 motion sensor to capture human motions and imitation by the humanoid robot with legged motion
    url: https://ieeexplore.ieee.org/document/8610719
    btn_label: "Paper"
    btn_class: "btn--success"
  
  - image_path: /images/projects/tic-tac-toe.gif
    title: Tic-Tac-Toe Playing Humanoid
    alt: "Tic-Tac-Toe Playing Humanoid"
    excerpt: A humanoid robot capable of playing tic-tac-toe against and human opponent, powered by the minimax algorithm. 

  - image_path: /images/projects/balance.gif
    title: Self Balancing Humanoid
    alt: "Dynamic Lateral balance"
    excerpt: Humanoid capable of self balancing on unstable surfaces like a suspension bridge
    url: https://ieeexplore.ieee.org/abstract/document/8284564
    btn_label: "Paper"
    btn_class: "btn--success"


---
<!-- <p style="text-align: center; font-size:42px;"> Projects </p> -->

<p style="text-align: center; font-size:24px;"> <b>Deep Learning for Resources and Environments</b> </p> 
Applied research focusing on applying machine learning and deep learning for resource and environmental modelling

![DeepGR4J](/images/projects/DeepGR4J.jpg){:.align-left .width-thirty}
**DeepGR4J**<br>
A synergy of Conceptual hydrological model GR4J and Convolutional Neural Network (CNN) and Long Short-term Memory (LSTM) neural networks for improved prediction performance in streamflow prediction tasks..<br>
[Code](https://github.com/arpit-kapoor/hybrid-gr4j){: .btn .btn--primary .align-right} [Paper](https://www.sciencedirect.com/science/article/pii/S1364815223002177){: .btn .btn--success .align-right}

<br>

<p style="text-align: center; font-size:24px;"> <b>Bayesian Machine Learning</b> </p> 
Various implementations of Markov Chain Monte Carlo Schemes for training Bayesian Neural Networks and other machine learning models.

![VaRNN](/images/projects/BRNN-Network.jpg){:.align-left .width-thirty}
**Variational Recurrent Neural Networks (VaRNN)**<br>
VaRNN provides implementation of Variational Bayes algorithm (inspired by [bayes-by-backprop](https://proceedings.mlr.press/v37/blundell15.html)) for RNN models including Long Short-term Memory models. We apply these models for prediction of cyclone tracks and intensities in data provided by Joint Typhoon Warning Center (JTWC).<br>
[Code](https://github.com/DARE-ML/variational-rnn-cyclones){: .btn .btn--primary .align-right} [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1364815223000403){: .btn .btn--success .align-right}

<br>


![EVO](/images/projects/evo-mcmc.jpg){:.align-left .width-thirty}
**Parallel Tempering for Bayesian Neuroevolution**<br>
The proven effectiveness of neuroevolution in Deep Learning ([here](https://eng.uber.com/deep-neuroevolution/)) is the motivation behind this project. This project investigates the effectiveness of multi-core implementation of parallel MCMC for population based Bayesian neuroevolution in pattern classification and time series problems.<br>
[Code](https://github.com/sydney-machine-learning/pt-bayesian-neuroevolution){: .btn .btn--primary .align-right} [Paper](https://www.sciencedirect.com/science/article/pii/S1568494622006056){: .btn .btn--success .align-right}

<br>


![BNTL](/images/projects/bntl.png){:.align-left .width-thirty}
**Bayesian Neural Transfer Learning** <br>
Quantify uncertainity in Tranfer Learning with Bayesian Neural Networks trained via Markov Chain Monte Carlo <br>
[Code](https://github.com/sydney-machine-learning/Bayesian-neural-transfer-learning){: .btn .btn--primary .align-right} [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231219314213){: .btn .btn--success .align-right}

<br>

<br>

![Surrogate-PT-NN](/images/projects/Surrogate.jpg){:.align-left .width-thirty}
**Surrogate-assisted Parallel Tempering for Bayesian Neural Networks** <br>
We use surrogate model to estimate the computationally expensive objective functions in Parallel Tempering to reduce the overall runtime of the MCMC sampling.<br>
[Code](https://github.com/sydney-machine-learning/surrogate-assisted-parallel-tempering){: .btn .btn--primary .align-right} [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0952197620301299){: .btn .btn--success .align-right}

<br>

![Surrogate-Bayeslands](/images/projects/cm_final.png){:.align-left .width-thirty}
**Surrogate-assisted Parallel Tempering Bayeslands**<br>
Surrogate-assited tempered MCMC algorithm for parallelized Bayesian inference for parameters of a landscape topography evolution model called [Badlands](https://github.com/badlands-model/badlands)<br>
[Code](https://github.com/intelligentEarth/surrogate-pt-Bayeslands){: .btn .btn--primary .align-right} [Paper](https://gmd.copernicus.org/articles/13/2959/2020/gmd-13-2959-2020.html){: .btn .btn--success .align-right}

<br>

<br>
---
<p style="text-align: center; font-size:24px;"> <b>Humanoid Robotics</b> </p> 

{% include feature_row%}

<br>

<p style="text-align: center; font-size:24px;"> <b> Undergraduate Final Year Thesis </b> </p> 

![Maze Solver](/images/projects/maze.png){:.align-left .width-half}
**Humanoid Maze Solver using Deep Reinforcement Learning** <br>
<p style="text-align: justify; ">A Heirarchical Reinforcement learning inspired approach used to teach a higher order task (solving a maze) to a humanoid. The approach consists of two policies: a higher level maze solver policy, and a lower level Humanoid mobility policy. The simulation was generated in a MuJoCo environment.</p> 
[Project](https://github.com/arpit-kapoor/RL-Humanoid){: .btn .btn--primary}

<br>

<p style="text-align: center; font-size:24px;"> <b> Software Packages </b></p> 
**Pynamixel** <br>
Python module written on top of DynamixelSDK to provide convinient interface with [Robotis Dynamixel Smart Robotic Actuators](http://www.robotis.us/dynamixel/) <br>
[Code](https://github.com/SRM-Team-Humanoid/pynamixel){: .btn .btn--primary}

**ROS Dynamixel** <br>
Robot Operating System (ROS) package that provides a ROS Message interface to interact with Dynamixel Actuators <br>
[Code](https://github.com/SRM-Team-Humanoid/ros_dynamixel){: .btn .btn--primary}

<br>