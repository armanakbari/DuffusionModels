# Duffusion Models

Diffusion models are a type of generative model used in machine learning and statistics. They are designed to capture the dynamics of how data evolves over time through a process of gradual diffusion or spread. These models are particularly useful for modeling complex distributions, such as images or time series data.

At a high level, diffusion models work by iteratively transforming an initial sample (usually random noise) into the desired data distribution through a sequence of steps. Each step involves adding a controlled amount of noise to the current sample, making it gradually resemble the target distribution. This iterative process continues until the final generated sample is sufficiently close to the desired distribution.

The defining characteristic of diffusion models is that they model the data generation process in reverse, starting from a high level of noise and gradually refining it to create realistic samples. This is in contrast to traditional generative models like Generative Adversarial Networks (GANs) or Variational Autoencoders (VAEs), which generate samples from a low-dimensional noise space and map them to the data space.

Herer is a basic implementation of these models.


<img src="https://github.com/armanakbari/DuffusionModels/blob/main/download.png">
