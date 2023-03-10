# TFM-GAN
Generative adversarial network for faking flower images.
The document of this project, with more image generated flowers can be found in https://oa.upm.es/71209/




It even fakes the Google lens detector by making it thinks that the images generated are real flowers

ABSTRACT

One of the areas currently being studied by Artificial Intelligence (AI) is image generation. Two of the most important techniques in deep learning are variational autoencoders (VAE) and generative adversarial networks (GAN). The architecture of the GAN consists of two networks of neurons, one generative and the other discriminative, set to compete with each other. The generator learns to produce data that resembles the training set, while the discriminator must learn to distinguish whether the samples are real (from the data set) or fake (images produced by the generator). A subset of GANs are deep convolutional adversarial generative networks (DCGAN). They use filters to extract patterns when the dataset has 2 or more dimensions. They are most suitable when generating images or representations of objects in three dimensions. The objective of this work is the implementation of a DCGAN for the generation of fake images of flowers from a normally distributed random input. For the training of the network, a public repository with images of flowers is used. The development of this project consists of 4 phases: acquisition of the necessary knowledge of DCGANs and Python´s APIs (Tensorflow, Keras), designing the deep neural network, the implementation and finally, testing. The results obtained are favorable, given that in the training of the DCGAN it has been possible to reach a point of equilibrium between the two networks. The images produced by the generator resemble real flowers, which is verified by using Google Lens. The main application of this network is to generate new images of flowers to produce data sets for the purpose of training other neural networks. The generated images can also be used for design, or as inspiration for paintings, clothing, films or video games where new designs of non-existing flowers or a large number of different flowers are required.

