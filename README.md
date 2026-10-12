# fruit-image-classifier
A CNN-based fruit image detection system built with Keras and TensorFlow

## OVERVIEW
- This project uses a CNN (Convolution Neural Network), along with the Keras and TensorFlow libraries, which takes images of either an apple, orange, or banana and correctly outputs what the given image is.
- The project is currently a work in progress with an initial CNN implemented and methods to reduce overfitting and improve generalization underway

## TECHNOLOGIES
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pillow

## CURRENT IMPLEMENTATION
- image loading and resizing using TensorFlow
- A CNN architecture with convolution layers, max pooling, and dense layers.
- Model training using the Adam optimizer and sparse categorical cross-entropy.
- Training and validation accuracy/loss visualization.
- Using data augmentation like random flips, rotations, and zoom.

## CURRENT CHALLENGES
- The current model shows problems with overfitting with our validation and training loss graphs showing incorrect results
- The project is still in its development phases with further model tuning remaining an area which needs improvement

