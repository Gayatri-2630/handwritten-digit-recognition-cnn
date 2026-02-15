# Handwritten Digit Recognition using CNN

## Overview
This project builds a Convolutional Neural Network (CNN) model to recognize handwritten digits using the MNIST dataset.

## Dataset
- MNIST handwritten digit dataset
- 70,000 images
- Classes: digits 0–9

## Model Architecture
- Conv2D layers
- MaxPooling
- Flatten
- Dense layers
- Dropout
- Softmax output

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib

## Results
The model successfully classifies handwritten digits with high accuracy.

## Project Structure
- digit_cnn_model.ipynb → training + prediction code
- images/ → output screenshots
- requirements.txt → dependencies

## How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Run the notebook:
   digit_cnn_model.ipynb

## Future Improvements
- Deploy as a web app
- Real-time digit recognition
- Improve model accuracy
