# Seismic Denoising with Vision Transformer (ViT)

This repository contains a Jupyter Notebook implementing **seismic data denoising** using a **Vision Transformer (ViT)** model. The notebook applies a transformer-based approach to enhance seismic signals by reducing noise, leveraging **Masked Autoencoder (MAE)** techniques.

## Features
- **Vision Transformer (ViT) for Denoising**: Uses a transformer-based architecture instead of traditional convolutional networks.
- **Masked Autoencoder (MAE)**: Implements a self-supervised learning technique for feature extraction and noise removal.
- **Custom Loss Functions**: Optimized loss metrics to enhance denoising performance.
- **Testing & Evaluation**: Includes testing framework to analyze model performance on seismic datasets.

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/SimLab120/SeisDenoiser.git
cd SeisDenoiser
pip install -r requirements.txt

