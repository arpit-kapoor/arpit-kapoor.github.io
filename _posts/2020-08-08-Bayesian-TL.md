---
title: "Bayesian Neural multi-source Transfer Learning"
layout: single
date: 2020-08-08
tags: [machine learning, neural network, mcmc, transfer learning]
header:
    image: "/images/bntl/header-1.jpg"
excerpt: "Markov Chain Monte Carlo Sampling for Tranfer Learning in Neural Networks"
mathjax: true
---

# Introduction

We humans possess the capability to apply the knowledge from different domains and combine this knowledge to solve a similar problem lying in a different domain. For example, a person capable of riding a bicycle and a manual car can use the knowledge of how to balance a two wheeler bicycle and the knowledge of how to operate a cars and combine these two information together to learn how to ride a Motorcycle. This ability to transfer and combine knowledge from different domains to solve a new problem is very crucial in human beings.

Transfer learning is a domain of machine learning which tries to mimic this capability of using knowledge from task to solve a different task. Whereas, multi-source transfer learning tries to combine knowledge learnt from various task together to facilitate learning of a target task.

In Bayesian multi-source transfer learning, we model this problem using a bayesian framework. Bayesian methods provides a probabilistic representation of the model that naturally accounts for uncertainty in decision making which have a wide range of applications in various domains that include machine learning, econometrics, environmental and Earth sciences. This framework uses Random walk via Markov Chain Monte Carlo to train a neural networks to solve the problem of transfer learning.

# Bayesian Neural Networks via MCMC

Bayesian Neural networks (BNN) are artificial neural networks where the weights and biases of the neural network are represented using a probability distribution. There are various ways of training bayesian neural networks, one such way is using Markov Chain Monte Carlo sampling which is used to estimate the *Posterior distribution* for parameter of interest (neural network weights in this case).

If you are new to MCMC, *Ben Shaver* has written a [blog](https://towardsdatascience.com/a-zero-math-introduction-to-markov-chain-monte-carlo-methods-dcba889e0c50) explaining the basics of MCMC. I would recommend checking it out.

<img src="https://www.researchgate.net/profile/Seung_Seop_Jin/publication/334001505/figure/fig1/AS:773761095696384@1561490429013/Illustration-of-Markov-Chain-Monte-Carlo-method.ppm" alt="MCMC">

In essence, MCMC uses bayesian inference in a markov chain where a new sample value (parameter of interest) is drawn from the *Proposal distribution* (using the previously sampled value) repeatedly. These porposals are accepted/rejected based on the *likelihood and prior probability density funtion* values. All the accepted samples form the *Posterior distribution* for our parameter of interest.

## MCMC Random Walk on Neural Network parameters

We will use a shallow network with only three layers *(Input, Hidden and Output)*. Let $$θ = (w , v, β, µ)$$ that features a total of $$L$$ weights and biases. The feedforward neural network topology with one hidden layer is defined by the number of input $$(I)$$ , hidden $$(H)$$ and output $$(O)$$ neurons, respectively. Given single input instance $$x$$ with corresponding label $$y$$ from dataset $$Ω$$, the network computes the output $$fo(x)$$ for a neuron $$o$$ in the output layer by

$$f_o(X) = g(\beta_o + \displaystyle \sum_{j=1}^H v_{jo} * g(\mu_j + \displaystyle \sum_{d=1}^I w_{dj}x_d))$$









<!-- # H1

## H2

Here's some text

Here's some *italics*

Here's some **bold** text

Here's an image:

<img src="{{ site.baseurl }}/images/neuroevolution/linsep.jpg" alt="waterfront">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/neuroevolution/linsep.jpg)


Here's some math
$$z=x+y$$ 

inline: $$z=x+y$$ -->