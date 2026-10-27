# Cats vs Dogs Classification with ResNet50 and Grad-CAM

## Overview
This project uses a pretrained ResNet50 convolutional neural network to classify cat and dog images. Grad-CAM heatmaps are generated to visualize image regions influencing the model's predictions.

## Technologies
- Python
- PyTorch and Torchvision
- NumPy, Pandas, Matplotlib
- Google Colab

## Workflow
1. Load and inspect the dataset.
2. Preprocess images using ResNet50's pretrained transformations.
3. Generate cat-versus-dog predictions.
4. Evaluate predictions on the selected image subset.
5. Visualize correct and incorrect predictions.
6. Generate Grad-CAM heatmaps and overlays.

## Limitations
The model uses ImageNet pretrained weights and is not fine-tuned specifically on this dataset. Results depend on the dataset labels, ImageNet class mapping, and selected images. Grad-CAM visualizations are explanatory approximations, not proof of model reasoning.

## Dataset
Cats and Dogs dataset: https://www.kaggle.com/datasets/yashdogra/cats-and-dogs

## Running the project
Open the notebook in Google Colab and run its cells in order. Follow the notebook instructions to download the dataset.
