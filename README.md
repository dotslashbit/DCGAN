# DCGAN
This is an implementation of DCGAN using pytorch.
The paper for this implemention is https://doi.org/10.48550/arXiv.1511.06434  

- This paper propose and evaluate a set of constraints on the architectural topology of Convolutional
GANs that make them stable to train in most settings. This class of architectures is known as Deep Convolutional GANs (DCGAN).  
- This paper used the trained discriminators for image classification tasks, showing competitive per-
formance with other unsupervised algorithms.

This paper used CNN for both the discriminator and the generator, and obviously this architecture performed better than the simpleGAN.  
The CNN architecture for generator is literally the inverse of what a normal CNN architecture is. This paper also mentions specific hyperparameter values and regularization paramters for this DCGAN implementation.
