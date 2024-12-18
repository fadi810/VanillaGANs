Simple Vanilla GAN Implementation
This repository contains a basic implementation of a Vanilla Generative Adversarial Network (GAN) for educational purposes. The goal of this project is to demonstrate the core concepts behind GANs, including the generator and discriminator networks, and their training dynamics.

Overview
The model consists of:

Generator (G): The generator takes random noise as input and generates synthetic data (images).
Discriminator (D): The discriminator distinguishes between real data and fake data generated by the generator.
The networks are trained in a game-like fashion where the generator tries to fool the discriminator, and the discriminator tries to correctly classify the images as real or fake.

Since this implementation was created for a college assignment and due to limited computational resources, the model has not been extensively trained and may not generate high-quality images. The results presented are from a simple run with a basic architecture.

Training Information
Epochs: 50
Steps per epoch: 469
Final Training Loss:
Discriminator Loss: 0.7965
Generator Loss: 1.4601