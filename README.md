# ArtGAN
# CycleGAN for Artistic Image Generation

## Overview
This project implements a CycleGAN model to transform real images into artistic images using deep learning. The model is trained on a dataset of human faces and generates artistic-style outputs.

## Features
- **CycleGAN Architecture**: Uses a ResNet-based generator and PatchGAN discriminator.
- **Unpaired Image-to-Image Translation**: Transforms real images into artistic styles without requiring paired datasets.
- **Self-Supervised Training**: Uses cycle consistency and identity loss to maintain image features.
- **Gradio Interface**: Provides an interactive web UI for testing the model.

## Tech Stack
- **Programming Language**: Python
- **Deep Learning Framework**: PyTorch
- **Dataset**: Custom human face dataset
- **Web Interface**: Gradio
- **Visualization**: Matplotlib, PIL

## Results
- **Dataset Size**: 6973 image pairs
- **Training Time**: Varies based on GPU availability
- **Batch Size**: 32

## Sample output:

![image](https://github.com/user-attachments/assets/5cd0ed92-423d-4a10-a631-f4a5e7f1dfd9)

![image](https://github.com/user-attachments/assets/4ef7cd83-0893-43ef-b7f0-33dacd66cd92)
