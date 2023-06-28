---
title: Task Difficulty Prediction in Physical Human Interaction using EEG and Deep Learning
excerpt: "In this study we are using the EEG recording to predict the robot instability during physical human robot interaction."
date: 2019-07-01
author: "Hemanth Manjunatha"
draft: false
categories:
- human-robot-interaction
- python
layout: single
links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/HemuManju/reaction-time-classification
- icon: paperclip
  icon_pack: fas
  name: paper
  url: https://github.com/HemuManju/reaction-time-classification
coverwidth: 300px
---

## Abstract

An experiment was conducted in which the subjects have to guide an robot under admittance control through a predefined trajectory. The damping in the admittance control was changed from low to high during different trials. Due to low damping, the controller might become unstable during the force input from the human subject. To quantify the instability, a frequency domain measure has been extracted from the force data. During the whole experiment scalp EEG was recorded and used to predict whether the robot becomes unstable during the co-manipulation. This was achieved by constructing a regression with EEG features as input and instability index as output. For the prediction model, we are leveraging the deep learning technique namely convolution neural networks.
