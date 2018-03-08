---
layout: post
title: "Deep Learning Project"

---

Project Title: On the Training of Generative Adversarial Nets

Team Members: Mingrui Liu, Xin Man, Shuyang Fu

A. Project Idea

Standard Generative Adversarial Net (GAN) suffers from the instablity and failure to achieve convergence during the training phase. To address this issue, there are two common strategies. The first is to change the objective function in a smart way to make it easier to train while maintaining its the effectiveness, and another way is to utilize different optimization algorithms to accelerate the training procedure. In this project, we aim to investigate and design different approaches for training GANs based on the both strategies. Concretely, we target on following recent developments of different GANs, specifying different objective functions, establishing theoretical results mathematically, and investigating a variety of optimization algorithms to facilitate efficient training. 

B. Dataset Details

There are many ideally existing datasets available, including MNIST, the Toronto Face Database (TFD), CIFAR-10, etc. 

C. Software

All codes will be developed under the pytorch framework. We will implement different network architectures and optimization algorithms. 

D. Relevant Papers

1. Generative Adversarial Nets, Ian J. Goodfellow et al, NIPS 2014.
2. Towards Principled Methods for Training Generative Adversarial Networks, Martin Arjovsky and Leon Bottou, ICLR 2017.
3. Wasserstein Generative Adversarial Networks, Martin Arjovsky et al, ICML 2017.
4. Improved Training of Wasserstein GANs, Ishaan Gulrajani et al, NIPS 2017.


E. Progress Milestones

1. Before April 1st, get experimental results for GAN and WGAN, and (probably) another variant of GAN by using standard primal-dual mini-batch SGD update.
2. Before May 1st, get experimental results by using different optimization algorithms, including ADAM, SGD, etc, and compare them with the results using objective function we specified. In addition, we try to get some theoretical understanding of different algorithms.

Below is a goofy page:

![My helpful screenshot]({{ "/assets/u=1659331746,2979952409&fm=21&gp=0.jpg" | absolute_url }})

Wanna [get some pdf?]({{ "/assets/01Intro.pdf" | absolute_url }}) 
