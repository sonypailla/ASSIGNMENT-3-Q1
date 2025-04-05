# Basic Autoencoder on MNIST Dataset

## Student Information

- **Name**: Sony Pailla  
- **Course**: CS5720 Neural Network and Deep Learning (Spring 2025)  
- **University**: University of Central Missouri  
- **GitHub**: [sonypailla](https://github.com/sonypailla)

---

## Overview

This project implements a **Basic Autoencoder** using the MNIST dataset. An autoencoder is an unsupervised neural network that learns to compress and then reconstruct its input data. The goal is to explore how dimensionality reduction affects reconstruction quality.

---

## Objectives

1. Load the MNIST dataset.
2. Define a fully connected (Dense) autoencoder:
   - Encoder: 784 → 32
   - Decoder: 32 → 784
3. Compile and train the model using binary cross-entropy loss.
4. Visualize original vs. reconstructed images.
5. Analyze how modifying the latent size (e.g., 16, 64) affects performance.

---

## Dependencies

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib

