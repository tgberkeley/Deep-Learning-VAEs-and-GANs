# Deep_Learning_Generative_Models_VAEs_and_GANs 

Imperial College Deep Learning Coursework 2 2020-2021

The VAEs_and_GANs.ipynb file is divided in two parts (reproduced in vaes_and_gans.py as GitHub cannot open very large ipynb file).

* The first part consists in a variational autoencoder used in the MINST dataset. In adition to the implementation, the following is shown or discussed

Reconstruction samples and a few generated samples are shown

How does the loss function relate to the VAE prior, the output data domain, and disentanglement in the latent space

Behaviour of the log-likelihood loss and the KL loss by observing their graphs

Posterior collapse

Role of the KL loss term and 𝛽 in the latent representation of the test set (visualized using T-SNE)

Interpolation in the latent space is shown

* The second part consists of a Deep Convolutional GAN implementation in the CIFAR-10 dataset. Some important features of the implementation are:

Batch normalisation

ReLU activation in the generator, and Leaky ReLU activation in the discriminator

Data augmentation - RandomCrop and RandomHorizontalFlip

The following topics are discussed in the second part:

Generator and discriminator's loss curves

Mode collapse

_This repository also contains the final trained models for the VAE, the GAN generator, and the GAN discriminator_
