# Uncertainty-Aware Deep Learning for Robust Chest X-ray Interpretation

## Project Overview
This project aims to classify medical images from the CheXpert dataset using various deep learning architectures including EfficientNetB0, DenseNet121, and a custom CNN model. The models are trained and evaluated on a subset of the CheXpert dataset, focusing on multi-label classification of chest X-rays.

The CheXpert dataset is a large dataset for chest X-ray interpretation, featuring uncertainty labels and pathologies. 

This project explores:
- EfficientNetB0: A pre-trained model fine-tuned for the CheXpert dataset.
- DenseNet121: Another pre-trained architecture fine-tuned for this task.
- Custom CNN Model: A convolutional neural network built from scratch for baseline comparisons.
  
## Dataset
- **Name**: CheXpert
- **Source**: [CheXpert Dataset](https://paperswithcode.com/dataset/chexpert)
- **Description**: The CheXpert dataset includes images and labels for a range of chest pathologies. The key target classes are:
- Atelectasis
- Cardiomegaly
- Consolidation
- Edema
- Pleural Effusion
  
## Objectives
- Train models to detect chest pathologies from X-rays.
- Implement uncertainty estimation in predictions to enhance model reliability.
  
## Models Used
- EfficientNetB0: Transfer learning with ImageNet pre-trained weights. Added global average pooling, dense layers, batch normalization, and dropout for fine-tuning.
- DenseNet121: Transfer learning with ImageNet pre-trained weights. Similar architecture to EfficientNetB0 for fine-tuning.
- Custom CNN Model: Built from scratch using Conv2D, MaxPooling2D, Dense layers, and Dropout. Used as a baseline model.


## Preprocessing Steps
- Images are rescaled and normalized.
- Data augmentation includes random rotations, shifts, and flips.
- The data is split into training, validation, and test sets.

### Dependencies
- Python 3.8 or higher.
- TensorFlow 2.4 or higher.
- GPU-enabled machine for training (recommended).

### Usage
- Clone the repository:
   ```bash
   git clone https://github.com/deepikamokkati/project.git
- Download the CheXpert Dataset: Place the dataset in the input/chexpert-v10-small directory.
- Run the Notebook or Scripts: Execute the provided Jupyter Notebook or Python scripts to train and evaluate the models.
- Visualize Results: Use the provided plotting functions to analyze training metrics.
