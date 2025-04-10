# Retinal Vessel Segmentation on the DRIVE Dataset

This project explores two deep learning models for **semantic segmentation** of blood vessels in retinal images, utilizing few-shot fine-tuning techniques:

- **UNet** (Convolutional Neural Network)
- **SegFormer** (Transformer-based architecture)

The goal is to segment vessels from retinal images using the **DRIVE** dataset, which contains 20 training images and 20 testing images.

## Models & Experiments

- Both models are trained and evaluated on the same dataset.
- Metrics like accuracy and loss are plotted and compared.
- Example predictions are visualized below.

## Preview

![Preview](![alt text](image.png))

## Dataset

Dataset used:  
[DRIVE: Digital Retinal Images for Vessel Extraction](https://github.com/rohit9934/DRIVE-Digital-Retinal-Images-for-Vessel-Extraction)


## 🛠️ Requirements

- torch
- torchvision
- transformers
- matplotlib
- scikit-learn
- PIL
