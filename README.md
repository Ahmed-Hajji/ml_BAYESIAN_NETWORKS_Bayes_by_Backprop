# Introduction
This project aims at implementing the ```Bayes By Backprop``` algorithm. This algorithm was first presented by Google DeepMind in the paper [Weight Uncertainty in Neural Networks](https://arxiv.org/abs/1505.05424). There, the algorithm is explained and 3 different applications are suggested.
- Classification on MNIST
- Regression curves
- Bandits on Mushroom Task

In this project, the focus is on the non-linear regression task. Experimental results similar to the published results [section 5.2 of the paper] have been achieved.

Epistemic uncertainty is explored and quantified in regions with no data. A confidence interval/region is displayed to showcase possible extrapolation results of the used Bayesian neural network.


# Setting
The project is developped in Python using ```PyTorch```. In order to facilite running the code and reproducing the results, a ```requirements.txt``` is provided with the needed libraries.  
