# Uncertainty-Aware Deep Learning for Robust Chest X-ray Interpretation

## Project Overview
This project explores the use of uncertainty-aware deep learning models to improve the robustness and reliability of chest X-ray interpretation. We leverage the CheXpert dataset, a large labeled dataset of chest X-rays, to train and evaluate models that can detect various chest pathologies.

## Dataset
- **Name**: CheXpert
- **Source**: [CheXpert Dataset](https://paperswithcode.com/dataset/chexpert)
- **Description**: A large dataset for automated chest X-ray interpretation with uncertainty labels for 14 observations.
  
## Objectives
- Train models to detect chest pathologies from X-rays.
- Implement uncertainty estimation in predictions to enhance model reliability.
  
## Models Used
- ResNet50
- DenseNet121
- Other uncertainty-aware architectures

## Preprocessing Steps
1. Handle missing or uncertain labels.
2. Resize images to fit model input dimensions.
3. Normalize pixel values for model compatibility.

## Getting Started
### Dependencies
- Python 3.7+
- TensorFlow
- PyTorch
- Pandas
- NumPy

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/deepikamokkati/project.git
