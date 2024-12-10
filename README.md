In this project, I'll use variational autoencoder under 3 differents versions to try generating new molecules
The task is hard because the dataset is small and the varaibility of characters is also small

The first version is a simple VAE with a standard gaussian prior

The second one is using an enhanced regularizer

The last one create a latent version of the dataset using an autoencoder, create a prior over this latent dataset and then using it as the prior in the VAE
