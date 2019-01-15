# GAN-TF-Keras
The ```MNIST_GAN.ipynb``` notebook is a sample GAN network provided by TensorFlow demonstrating the Keras API.

In ```MNIST_cGAN.ipynb```, I adapt the code to build a conditional GAN for the MNIST dataset. This primarily required reworking the generator and discriminator models using the Keras Functional API (instead of Sequential API). By doing so I was able to create an embedding of the labels for the MNIST dataset to be fed into the Generator/Discriminator. 

I used these notebooks to learn the construction of GANs and cGANs, and applied them to my own datasets in my ```Ising-Deep-Learning``` Repo!
