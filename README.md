# Autoencoders
These are a collection of autoencoders of different types each trained using MNIST digits and fashion. They are experiments in dimensionality reduction and classification based on latent variables.

### Files:

| File Name | Explanation |
| --------- | ----------- |
| ae.ipynb | A basic autoencoder made out of only densly connected neurons |
| cae.ipynb | An autencoder build from convolutional layers and one densly connected layer to act as the latent space |
| vae.ipynb | A basic variational autoencoder that can act as a generative model |
| vcae.ipynb | A convolutional autoencoder that can act as a generative model |
| direct_num_classifier.ipynb | A basic mlp classifier to be compared agains the one using the dimensionality reduced output from an autoencoder |
| num_classifier.ipynb | A classifier that uses the output from an autoencoder as its input |

### Basic Architecture:

![vae architecture](https://i.imgur.com/rJY6kKy.png)
