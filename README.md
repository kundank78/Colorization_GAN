# Colorization_GAN
Gray-scale Image Colorization using Conditional Generative Adversarial Network.
This is a PyTorch implementation of the DCGAN as described in the paper [Image Colorization using
Generative Adversarial Networks](https://arxiv.org/pdf/1803.05400.pdf)

## Network Architecture
The architecture of generator is inspired by U-Net: The architecture of the model is symmetric, with n encoding units and n decoding units.
![alt text](https://github.com/kundank78/Colorization_GAN/blob/master/unet.png)
For discriminator, we use similar architecture as the baselines contractive path.
