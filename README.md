

## MNIST Digit Classification with CNN

### Overview
This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0-9) from the MNIST dataset. The model is trained using 5-fold Cross-Validation to ensure robust performance, with the best model saved for final evaluation.

### Features
- **Data Preprocessing:** Images are normalized and reshaped for input into the CNN.
- **Model Architecture:** Includes convolutional layers, pooling, fully connected layers, and dropout for regularization.
- **Cross-Validation:** 5-fold Cross-Validation is used to validate model performance across different data splits.
- **Model Saving:** The best model, based on validation accuracy, is saved using the `ModelCheckpoint` callback.
- **Evaluation:** The saved model is evaluated on the test set, with metrics like accuracy, precision, and confusion matrix visualized.

### Results
- **Training Accuracy:** Average of **99.32** across folds.
- **Validation Accuracy:** Average of **98.93** across validation sets.
- **Test Accuracy:** **99.19** on the test set using the best model.
- **Test Precision:** **99.19** (weighted average) on the test set.
- **Confusion Matrix:** Visualized for both validation and test predictions to understand classification performance.

