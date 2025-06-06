# Vegetable Image Classification with CNN

## Project Overview
This repository contains a deep learning project for classifying vegetable images using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. The model is trained on the [Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset) from Kaggle.

## Dataset Details
- **15 vegetable classes**: Bean, Bitter_Gourd, Bottle_Gourd, Brinjal, Broccoli, Cabbage, Capsicum, Carrot, Cauliflower, Cucumber, Papaya, Potato, Pumpkin, Radish, Tomato
- **Image size**: 256x256 pixels
- **Samples**:
  - Training: 15,000 images
  - Validation: 3,000 images
  - Test: 3,000 images
 
# ACCURACY :
- Training accuracy: ~91%
- Validation accuracy: ~95% 
- Test accuracy: ~95.5%

## Key Features

- Data preprocessing with normalization and resizing
- Early stopping and model checkpointing callbacks
- Visualization of training progress
- Model saving/loading functionality
- Example inference code (commented out)

## Requirements

To run this notebook, you'll need:
- Python 3.6+
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib

## Usage

1. Clone the repository
2. Download the dataset from Kaggle
3. Place the dataset in `/content/Vegetable Images/` (or update paths)
4. Run the notebook cells sequentially

## File Structure

- `vegetable_detection.ipynb`: Main Jupyter notebook with all code


## Results

The model shows excellent performance on vegetable classification, achieving 95%+ accuracy on both validation and test sets. Training curves show good convergence without overfitting.




