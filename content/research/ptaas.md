+++
author = "Asal Delkhosh, Prof. Sadeghian"
title = "ML: penetration testing model"
date = "2023-11-15"
description = "Implementing a machine learning model for automated penetration testing."
tags = [
    "machine learning",
    "svm",
    "nbias",
    "security",
    "networks"
]
+++

Implementing a machine learning model in order to find the attacks that can be performed during a penetration testing by using analysis result data which consists of system vulnerabilities, bugs, and bad smells.

<!--more-->

The project dataset is created with help of network and security engineers by analysing 3500 vulnerabilities and choosing the right attacks based on each state. Kinda like simulating 3500 penetration testing attack done by a human agent.

Our dataset is labelled and its linear, therefore, we are using supervised learning. Our algorithm is based on classification. Our two methods are:

- SVM: accuracy 86%
- Nbias: accuracy 92%
