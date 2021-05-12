---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D Candidate in Aalto University *(Feb. 2020 -- Now)*
  * Research Topic:  Reinforcement Learning with a Handful of Trials
  * Co-supervised by Prof. Juho Kannala and Prof. Joni Pajarinen
* MSc in Aalto University *(Sep. 2018 -- Oct. 2020)*
  * Grade: 4.7/5
  * Major in Control, Robotics and Autonomous System
* BEng in Huazhong University of Science and Technology

Publications and Theses
======
**Learning to Drive (L2D) as a Low-Cost Benchmark for Real-World RL**      ([Project Page](https://sites.google.com/view/donkeycar))
- We introduce Learning to Drive (L2D), a simple and easily reproducible Reinforcement Learning benchmark with a real small-scale car.
- Apply a model-based RL algorithm, named Dreamer, on a small-scale racing car, which learns to drive from scratch using raw pixels in less than five minutes of interaction.

**Hierarchical Scene Coordinate Classification and Regression for Visual Localization** ([Paper](https://arxiv.org/abs/1909.06216))
- We propose a hierarchical network to predict pixel scene coordinates in a coarse-to-fine manner to improve performance in large and ambiguous environments, published in IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2020.

**Master Thesis: Model-based Reinforcement Learning from Pixels** ([Thesis](https://drive.google.com/file/d/1iZiPjpGF-WBHmuCY7WQ5FHGV7Q5tdQeN/view?usp=sharing)，[Code](https://github.com/zhaoyi11/dreamer-pytorch)，[Talk](https://drive.google.com/file/d/12S-jz3gQu28kRuQP2gt2IcFd9gJnBzAA/view?usp=sharing))
- Reproduce the [Dreamer](https://arxiv.org/abs/1912.01603) paper, a model-based visual reinforcement learning algorithm. The results are tested on the Mujuco simulator.
- Extend Dreamer by combining policy learning and decision-time planning (CEM). 
- Partially reproduce the [Muzero](https://arxiv.org/abs/1911.08265) algorithm, a model-based reinforcement learning algorithm that combines learning and Monte Carlo Tree Search to improve sample efficiency.
- Extend the MuZero algorithm to continuous control by discretizing the action space.

**Bachelor Thesis: Hardware and Software Design of Drones**
- Design the electronic circuits and PCB of the flight control unit.
- Implement a PID controller of quadcopters based on the STM32 microcontroller.
- Assemble a quadcoptor from scratch and test the implemented controller.
- Run Tracking-Learning-Detection algorithm and verify its performance.

Intern
======
**Research Assistant: Aalto Computer Vision Group**
- Propose a hierarchical network to predict pixel scene coordinates in a coarse-to-fine manner to improve performance in large and ambiguous environment with colleagues.
- Implement a simple structure-from-motion algorithm to construct 3D sparse models of indoor environments with repeated feature pattern.

**Summer Intern: Aalto Computer Vision Group**
- Implement an Android App for indoor visual localization in a client-server way. 
- Implement an Android App to collect dataset used for visual localization tasks.

Projects
========
**Reproduce Model-free RL Algorithms**
- Reproduce two model-free reinforcement learning methods, including PPO and SAC. ([Code](https://github.com/zhaoyi11/RL-pytorch))

**Bayesian Deep Learning**
- Implement and compare a set of Bayesian neural network methods, including MC Dropout, Concrete Dropout and Variational Dropout. ([Slides](https://drive.google.com/open?id=1KzYJ2NNP6in3aOwAihZ586I5Gfu7AwoF), [Code](https://github.com/zhaoyi11/Deep_Learning))

**ViTa-bot: A Bio-mimetically Transformed Youbot**
- The ViTa-Whisker array is a biomimetic tactile sensor array, inspired by whiskers of rodents. Its purpose is to explore its most immediate environment with whisking movement, and generate a pointcloud model which describes the 3D map of surroundings. ([Project Page](https://wiki.aalto.fi/display/AEEproject/ViTa-bot\%3A+A+bio-mimetically+transformed+Youbot))

**Reinforcement Learning Course Project**
- Implement DQN and Double DQN algorithms with autoencoder to play Atari games.

Skills
======
- **Programming:** Proficient in Python and past experience with C, C++, Java, MATLAB and other languages.

- **Tools:** Proficient in PyTorch, Numpy, OpenCV, Git, Bash, etc. Experience with TensorFlow, ROS, JAX, etc.
