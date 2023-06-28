---
title: Extracting Interpretable EEG Features from a Deep Learning Model to Assess the Quality of Human-Robot Co-manipulation
date: 2019-07-01
author: "Hemanth Manjunatha"
coverwidth: 500px
---

## Abstract

There is an increasing interest in adapting the deep learning models into neuroimaging techniques such as electroencephalogram (EEG). However, one of the fundamental problems in deep learning models is the interpretability of
the learned representations. Even though many interpretability models exist for computer vision applications, adapting those
methods for deep learning using EEG is still a challenge. In this regard, we propose a novel computational approach
to increase the interpretability of results from deep learning algorithm using two popular saliency detection algorithms:
integrated gradients and ablation attribution method. The method provides the importance of values across different EEG frequency bands (Theta, Alpha, Beta, Gamma) and across different electrode locations. We can use these importance values to recognize which electrode and frequency bands are relevant for a particular classification problem. We demonstrate
the proposed method’s efficacy in a physical human-robot co-manipulation experiment where a convolution neural network
(CNN) model is trained to classify the user’s mental workload using raw EEG recordings. The experiment is predominantly visuospatial and motor control-oriented. The proposed method found the Gamma and Beta frequency band across parietal and occipital regions to be important, which are indeed associated with visuospatial processing and sensory integration.

<p align="center">
  <img src="overview.jpg" width="200" />
</p>

## Results

**The study set out to answer two questions:**

* Which physiological modalities, eye, brain activity, or their combination can provide a more accurate classification of the reaction time?
* Do the task type information and individual differences in the task performance influence the classification of reaction time?

The study concluded that both eye features and cognitive features are needed to classify the reaction time effectively. The task type information had a significant influence on the classification accuracy, while the same could not be said with individual difference information. The accuracy of classification was increased when task type information was included as features, indicating that the reaction time depends on the task information.

These results are in agreement with the Linear Approach to the Threshold with Ergodic Rate (LATER) model, which suggests that reaction time depends on evidence collected and the task difficulty. The classifier trained on the physiological features using reaction time as the label can be used to classify task difficulty well above chance. Such systems can be utilized in Automation Invocation models that utilize appropriate control inputs and control strategies for optimal role allocation in collaborative tasks such as teleoperation.

|The present work showed that physiological measurements could indeed be used to model the task difficulty through auxiliary measurements such as reaction time|
|---|
