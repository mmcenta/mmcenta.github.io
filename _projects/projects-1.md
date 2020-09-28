---
title: "discrete-embeddings"
excerpt: "Tensorflow 2 implementations of VQ-VAE papers and experiments. <br/><img src='/images/discrete_embeddings.png'>"
collection: projects
---
[Link to repository](https://github.com/mmcenta/discrete-embeddings)

(Ongoing) I explore a class of Variational Autoencoders (VAEs) that bottleneck into discrete representations, which are called Vector Quantized Variational Autoencoders (VQ-VAE), introduced in [van den Oord et al. (2017)](https://arxiv.org/abs/1711.00937). I implement the models in TensorFlow 2 and experiment with a few different datasets. I also implement state-of-the-art generative models (such as [PixelCNN](https://arxiv.org/abs/1606.05328)) to learn priors over the discrete representations, which enables high-quality data generation.

I will continue working on this project to implement and test [VQ-VAE 2](https://arxiv.org/abs/1906.00446), [Jukebox](https://arxiv.org/abs/2005.00341) and [PixelSNAIL](https://arxiv.org/abs/1712.09763).

I also plan to conduct a little research experiment into [few-shot image generation](https://arxiv.org/abs/1710.10304) in the discretized embedding space, instead of the full image.
