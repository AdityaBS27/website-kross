---
title: "Probabilistic vehicle trajectories prediction using Inverse Reinforcement Learning"
date: 2019-09-23T12:14:34+06:00
image: "images/portfolio/GAIL.gif"
#client: "John Doe"
project_url : "https://github.com/AdityaBS27/DIRL"
categories: ["Data Science"]
description: "This is meta description."
draft: false
---

#### Project

The goal of the project was to achieve a suitable prediction model of driver’s intention,
in case of lane change scenarios to help in improving ADAS systems. The prediction
models must be robust to predict varied situations

#### Project Details

The project aimed to build a Deep Inverse Reinforcement
Learning (DIRL) model to analyze and learn diverse driving behaviour during lane
change scenarios. DIRL learns this behaviour by undergoing apprenticeship training
from an expert. It learns the reward structure of drivers decision during lane change
scenarios from such varied expert driving behaviour, and by utilizing these reward it
predicts driving decision.


DIRL model is built upon a sequential time series model and General Adversarial Imitation
Learning (GAIL). GAIL assists in learning the rewards and future trajectories
are predicted using the sequential model. The model is optimized using reinforcement
learning techniques by performing policy gradients on the rewards, that are obtained
from the GAIL. The model is trained on expert naturalistic driving data recorded
on German highways called HighD. The model predicts lateral, longitudinal position
and velocity of surrounding vehicles. The accuracy of these predictions is evaluated by
comparing these trajectories with expert data.



#### Images
![](/images/portfolio/2_5.png)
![](/images/portfolio/2_1.png)
![](/images/portfolio/2_2.gif)
![](/images/portfolio/2_3.gif)
![](/images/portfolio/2_4.png)
