
# Learning Laplacian-Beta-VAE


### Requirements
- Python >= 3.5
- PyTorch >= 1.3
- Pytorch Lightning >= 0.6.0 ([GitHub Repo](https://github.com/PyTorchLightning/pytorch-lightning/tree/deb1581e26b7547baf876b7a94361e60bb200d32))
- CUDA enabled computing device

Pytorch implementation of [Laplacian-Beta-VAE].

This repo contains an implementation of Laplacian-Beta-VAE.


#### Example usage
```python
from jointvae.models import VAE
from jointvae.training import Trainer
from torch.optim import Adam
from viz.visualize import Visualizer as Viz
