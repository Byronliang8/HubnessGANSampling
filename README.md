[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Byronliang8/HubnessGANSampling/blob/main/Colab/Exploring_and_Exploiting_Hubness_Priors_for_High_Quality_GAN_Latent_Sampling.ipynb)

# Exploring and Exploiting Hubness Priors for High-Quality GAN Latent Sampling
Yuanbang Liang, Jing Wu, Yu-Kun Lai, Yipeng Qin
## Abstract 
Despite the extensive studies on Generative Adversarial Networks (GANs), how to reliably sample high-quality images from their latent spaces remains an under-explored topic. In this paper, we propose a novel GAN latent sampling method by exploring and exploiting the hubness priors of GAN latent distributions. Our key insight is that the high dimensionality of the GAN latent space will inevitably lead to the emergence of hub latents that usually have much larger sampling densities than other latents in the latent space. As a result, these hub latents are better trained and thus contribute more to the synthesis of high-quality images. Unlike the a posteriori ``cherry-picking'', our method is highly efficient as it is an a priori method that identifies high-quality latents before the synthesis of images. Furthermore, we show that the well-known but purely empirical truncation trick is a naive approximation of the central clustering effect of hub latents, which not only uncovers the rationale of the truncation trick, but also indicates the superiority and fundamentality of our method. Extensive experimental results demonstrate the effectiveness of the proposed method. 
Link of the paper: https://arxiv.org/abs/2206.06014

## Release notes
Our research is based on StyleGAN2; you can check the basic work through https://nvlabs.github.io/stylegan2/versions.html

## Requirements 
- Linux and Windows are supported, but we recommend Linux for performance and compatibility reasons.
- 64-bit Python 3.7 and PyTorch 1.7.1. See https://pytorch.org/ for PyTorch install instructions.
- CUDA toolkit 11.0 or later. Use at least version 11.1 if running on RTX 3090.
- Python libraries: `pip install click requests tqdm pyspng ninja imageio-ffmpeg==0.4.3` and `pip install scikit-hubness`. 

## Example results

