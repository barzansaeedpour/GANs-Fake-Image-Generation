# Fake Image Generation with Generative Adversarial Networks (GAN)

## Overview

This project demonstrates the use of Generative Adversarial Networks (GANs) to generate fake images for the MNIST dataset. GANs consist of a generator and a discriminator, which are trained simultaneously through adversarial training. The generator tries to create realistic images, while the discriminator tries to distinguish between real and fake images. You can use the same idea for othe datasets.

## About GANs

<img src= './files/architecture.png'/>

Generative Adversarial Networks (GANs) are a class of artificial intelligence algorithms used in unsupervised machine learning. They were introduced by Ian Goodfellow and his colleagues in 2014. GANs consist of two neural networks, a generator, and a discriminator, which are trained simultaneously through adversarial training.

### Components of GANs:

1. **Generator:**
   - The generator takes random noise as input and tries to generate data (e.g., images).
   - It learns to produce data that is indistinguishable from real data.

2. **Discriminator:**
   - The discriminator evaluates whether a given input is real (from the actual dataset) or fake (produced by the generator).
   - It is trained to improve its ability to distinguish between real and generated data.

### Training Process:

1. **Generator Training:**
   - The generator generates fake data.
   - The discriminator evaluates the fake data.
   - The generator aims to produce data that the discriminator classifies as real.

2. **Discriminator Training:**
   - The discriminator is trained on both real and fake data.
   - It learns to correctly classify real and generated data.
   - The generator continues to improve based on the feedback from the discriminator.

### Adversarial Training:

- GANs are trained in an adversarial manner, where the generator and discriminator are in a constant competition.
- The generator's goal is to produce realistic data that can fool the discriminator.
- The discriminator's goal is to become increasingly accurate in distinguishing real from fake data.

## Results

| Real | Fake |
|----------|----------|
| Real images from MNIST dataset | Fake Images Genereted by the trained GAN |
|<img src="files/real.png" alt="Image 1" >|<img src="files/fake.png" alt="Image 4">|



## Usage

You can work with this repository in two ways:

1. Clone the repository and run the notebook

2. Open the note book in Colab:
https://colab.research.google.com/github/barzansaeedpour/GAN-Fake-Image-Generation/blob/main/GAN-Fake-Image-Generation.ipynb


## Project Structure

- `GAN-Fake-Image-Generation.ipynb`: Script for training the GAN on the MNIST dataset.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute to the project by opening issues or submitting pull requests!