# Image Captioning with ResNet50 and LSTM

This repository contains a simple image captioning model that utilises a pretrained ResNet50 for image feature extraction and an LSTM for generating captions. The model is trained and validated on the COCO 2017 dataset, demonstrating its capability to generate descriptive captions for images. This project serves as a straightforward example of how to combine CNNs and RNNs for the task of image captioning.

## Overview

The image captioning model is structured as follows:
- **Feature Extraction**: Employs ResNet50, pretrained on ImageNet, to extract features from images.
- **Caption Generation**: Uses an LSTM to generate captions based on the extracted image features.
- **Training Data**: The model is trained on a subset of the COCO 2017 dataset, with 5000 images for training and 500 images for validation.

## Requirements

- Python 3.6 or newer
- TensorFlow 2.x
- NumPy
- PIL
- Matplotlib (for testing and visualisation)

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/your-github-username/image-captioning-resnet50-lstm.git
cd image-captioning-resnet50-lstm
