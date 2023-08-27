# Learning JAX as a PyTorch User

> [!IMPORTANT]
> This is a test.

As a PyTorch user, I found it somewhat challenging to get started with JAX due to its peculiar features (e.g., PRNG state management) and an ecosystem that may be confusing for beginners. This repo contains self-contained notebooks for deep learning models in JAX. In particular, I use the following libraries.

- JAX 
- Flax: for deep learning modules, analogous to `torch.nn`.
- Optax: for optimizers, analogous to `torch.optim` .
- Distrax: for distributions, analogous to `torch.distributions`.

## Models

The following models have been implemented.

- [x] Variational Autoencoder (for MNIST): [./notebooks/vae.ipynb](./notebooks/vae.ipynb)
- [ ] DDPM
- [ ] Linear Gaussian SSM
- [ ] Linear Gaussian SSM w/ Parallel Inference
