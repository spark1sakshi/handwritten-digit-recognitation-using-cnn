## MNIST Digit Classification with CNN
This project classifies handwritten digits from the MNIST dataset using a Convolutional Neural Network (CNN).
The model is trained with 5-fold Cross-Validation, and the best model is saved with the ModelCheckpoint callback. 
After training, the model's performance is evaluated on the test set, with accuracy and precision metrics reported.
Confusion matrices are plotted to visualize classification performance across different folds and the test set.
