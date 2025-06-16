# Monet Style Transfer with CycleGAN  
*Inspired by the Kaggle Competition: "I'm Something of a Painter Myself"*

This repository contains the implementation of a CycleGAN model to translate real-world photographs into paintings in the style of Claude Monet. The project demonstrates the use of unpaired image-to-image translation techniques for artistic style transfer.

## Project Overview

The goal of this project is to train a CycleGAN that learns Monet’s unique painting style and applies it to photographic images. The dataset includes thousands of Monet paintings and corresponding landscape photos, provided in both `.jpg` and `.tfrecord` formats by Kaggle.

## Key Features

- Implementation of CycleGAN using TensorFlow and Keras
- Custom training loop and loss functions (cycle consistency, identity loss)
- Data loading from TFRecord format for efficient training
- Image preprocessing and augmentation
- Monet-style image generation from real photos
- Model experimentation and evaluation through multiple versions

