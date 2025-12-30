# GAN MNIST

This project trains a Generative Adversarial Network (GAN) to generate handwritten digits similar to the MNIST dataset.

## Overview
- **Dataset**: MNIST (digits 0–9)
- **Model**: 
  - Generator: creates digit images from random noise.
  - Discriminator: distinguishes real MNIST digits from generated ones.
- **Goal**: The generator learns to produce realistic digits that can fool the discriminator.

## Requirements
- Python 3.8+
- PyTorch
- Matplotlib
- Torchvision

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
Run the notebook or script to start training.  
Generated samples will be shown in the last cell.

## Results
The generator gradually improves to produce digits resembling MNIST. Sample outputs are logged during training.

---
✨ A minimal GAN example for learning and experimenting with generative models.