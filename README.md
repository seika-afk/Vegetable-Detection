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
- `model_checkpoint.h5`: Saved model weights
- `my_model.keras`: Saved full model

## Results

The model shows excellent performance on vegetable classification, achieving 95%+ accuracy on both validation and test sets. Training curves show good convergence without overfitting.

## Future Improvements

- Experiment with different architectures
- Try transfer learning with pretrained models
- Add data augmentation
- Deploy as a web application

## License

This project uses the [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/) license, same as the original dataset.
