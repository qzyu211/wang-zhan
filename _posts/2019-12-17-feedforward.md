---
title: "Feedforward Neural Network"
date: 2019-12-17
tags: [machine-learning, artificial-intelligence, feedforward, neural-network]
excerpt: "Neural networks for beginners."
category: machine-learning
mathjax: "true"
---
# Motivation
This document is based primarily on the presentation of feedforward networks in *Pattern Recognition and Machine Learning* by Christopher M. Bishop and an object-oriented design from [David Selby](https://selbydavid.com/2018/01/09/neural-network/) who likewise was inspired by Denny Britz. In an algorithms course for my M.S. in Data Science, I was able to successfully program a variety of different algorithms but became frustrated with progress on the feedforward neural network. In the end, I only submitted a solution to the assignment utilizing a neural network package’s function.

To overcome this obstacle, I’ve decided to adapt Bishop’s formulas so that they can be easier to interpret (therefore, this document would likely serve best anyone who is familiar or working with Bishop's text). The work in this document likely has many flaws and so I am open to any criticism. It would be practical to consider this document as a version of a student's notes. The ideal audience are those that are new to neural networks and are interested in developing a quick ability to understand the math and programming aspects of a simple neural network.

*NOTE:* I would't say that this document is yet complete, as there are still tasks related to hyperparameter tuning which were not thoroughly discussed in my course. After I complete an upcoming course dedicated to neural networks, I hope to be able to either update this document or create a new one that includes more relevant information.
