# Generative-Model of VAEs
This project demonstrates how a Variational Autoencoder works by learning to:

- encode handwritten digit images into a compact latent space
- reconstruct the original images from that latent space
- generate new digit-like images

This project is useful for beginners who want to learn:

- autoencoders
- latent space representation
- image reconstruction
- generative deep learning

---

## Dataset

This project uses the **MNIST dataset**, which contains:

- **60,000** training images
- **10,000** test images
- grayscale handwritten digits from **0 to 9**
- image size: **28 × 28**

---

## Features

- Simple and beginner-friendly VAE implementation
- Built using TensorFlow and Keras
- Encoder, sampling layer, and decoder
- Reconstruction of test images
- 2D latent space visualization
- Generation of new handwritten digits

---

## Project Structure

```bash
mnist-vae/
├── vae_mnist.py
├── README.md
└── images/
Output

The program will generate:

training loss plot
reconstructed digit images
latent space visualization
generated handwritten digits
    ├── reconstruction.png
    ├── latent_space.png
    └── generated_digits.png
