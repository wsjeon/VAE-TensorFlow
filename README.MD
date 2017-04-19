# Variational Autoencoder in TensorFlow

- This code was forked from @y0ast and modified in this repository using TFSlim.

- This is an improved implementation of the paper [Stochastic Gradient VB and the Variational Auto-Encoder](http://arxiv.org/abs/1312.6114) by D. Kingma and Prof. Dr. M. Welling.

- This code uses ReLUs and ADAM optimizer, instead of sigmoids and ADAGrad. These changes make the network converge much faster.

- To run the MNIST experiment: `python main.py`
