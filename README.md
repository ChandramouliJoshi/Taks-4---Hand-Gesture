# Taks-4---Hand-Gesture
A CNN-based hand gesture recognition model was developed using the LeapGestRecog dataset to accurately classify 10 different hand gestures from image data, achieving near-perfect validation accuracy.
Overview

This project implements a Convolutional Neural Network (CNN) to accurately recognize and classify 10 different hand gestures from image data. The model is trained on the LeapGestRecog dataset and achieves near-perfect validation accuracy.

The system demonstrates how deep learning can be applied to gesture-based human-computer interaction.

Dataset

Dataset: LeapGestRecog

Total Images: 20,000

Number of Classes: 10

Gestures: palm, palm_moved, fist, fist_moved, thumb, index, ok, l, c, down

All images were resized to 64×64 pixels and normalized before training.

Technologies Used

Python 3.10

TensorFlow / Keras

NumPy

OpenCV

Scikit-learn

Matplotlib

Model Architecture

The CNN model consists of:

Conv2D layer with ReLU activation

MaxPooling layer

Conv2D layer with ReLU activation

MaxPooling layer

Conv2D layer with ReLU activation

MaxPooling layer

Flatten layer

Dense layer (128 units)

Dropout (0.5)

Output layer with Softmax activation (10 classes)

Performance

Training Accuracy: ~99%

Validation Accuracy: ~100%

Very low validation loss

The confusion matrix and classification report indicate highly accurate classification across all gesture categories.

Model Saving

The trained model is saved as:

hand_gesture_model.h5


It can be reloaded for inference or integrated into gesture-based applications.

How to Run

Clone the repository

Install required dependencies

Run the Jupyter Notebook

Train and evaluate the model

Conclusion

This project successfully demonstrates a high-accuracy hand gesture recognition system using deep learning, suitable for gesture-controlled systems and interactive applications.
