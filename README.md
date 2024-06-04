# Variational Autoencoder (VAE) Implementation from Scratch

Welcome to the Variational Autoencoder (VAE) implementation repository! This project demonstrates how to build a VAE from scratch using the MNIST dataset.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Variational Autoencoders (VAEs) are a type of generative model that learn to encode data into a latent space and decode it back to the original space. They are widely used in various applications, including image generation, anomaly detection, and data compression. This repository provides a step-by-step implementation of a VAE using Python and popular deep learning libraries.

For more study and understanding, you can visit [this link](https://faezehmfr.wixsite.com/curiousseekers/post/implementation-of-a-variational-autoencoder-vae-from-scratch-on-mnist-dataset).


## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or later
- `numpy`
- `torch`
- `torchvision`
- `matplotlib`
- `jupyter`

You can install the necessary packages using `pip`:

```bash
pip install numpy torch torchvision matplotlib jupyter
```

## Project Structure

```plaintext
Variational_Autoencoder/
│
├── data/
│   └── mnist/
│       └── [MNIST Dataset Files]
├── models/
│   └── vae.py
├── utils/
│   └── data_loader.py
├── VAE_MNIST.ipynb
├── train.py
├── README.md
└── requirements.txt
```

- data/: Contains the MNIST dataset.
- models/: Contains the model definition for the VAE.
- utils/: Contains utility functions, including the data loader.
- VAE_MNIST.ipynb: Jupyter notebook for training and visualizing the VAE.
- train.py: Script for training the VAE.
- README.md: Project README file.
- requirements.txt: List of required packages.

  ![image](https://github.com/FaezeMqFr/Variational_Autoencoder/assets/145299921/817f1666-43da-4452-b4a1-bfc8ea0ebf99)

