# Super-Resolution GAN for Photo Enhancement
## Overview
This project implements a Super-Resolution Generative Adversarial Network (SRGAN) to enhance and restore old or low-resolution photos. The model can upscale images by 4x while maintaining and improving visual quality.

## Features
- 4x image upscaling
- GAN-based image enhancement
- Automatic checkpointing system
- Support for various image formats
- Built with PyTorch

## Model Architecture
- Generator: ResNet-based architecture with residual blocks
- Discriminator: CNN-based architecture for adversarial training
- Training includes both content and adversarial losses

## Training Parameters
- Learning Rate: 0.0002
- Batch Size: 4
- Image Size: 256x256
- Epochs: 100
- Checkpoint Interval: 5 epochs
