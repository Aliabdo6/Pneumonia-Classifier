# Pneumonia Classifier

This project is a web-based application that uses machine learning to classify whether a chest X-ray image shows signs of pneumonia or not. The application is built using HTML, CSS, and JavaScript, and it utilizes the TensorFlow.js library to load and run a pre-trained machine learning model.

## Project Structure

The project consists of a single HTML file (`index.html`) that contains all the necessary HTML, CSS, and JavaScript code. The HTML code defines the user interface, which includes a file input field for selecting an image, buttons for loading the model and making a prediction, and div elements for displaying the image, status messages, and prediction results.

The JavaScript code is responsible for loading the model, preprocessing the input image, making a prediction, and displaying the results. The code is organized into several functions that are called in sequence to perform these tasks.

## How to Use

To use the application, follow these steps:

1. Open the `index.html` file in a web browser.
2. Click the "Load Model" button to load the pre-trained machine learning model.
3. Click the "Choose File" button to select a chest X-ray image.
4. Click the "Predict" button to make a prediction.

The application will display the prediction results, indicating whether the image shows signs of pneumonia or not.

## Technical Details

The machine learning model used in this application is a convolutional neural network (CNN) that was trained on a dataset of chest X-ray images. The model takes as input a 224x224 grayscale image and outputs a probability distribution over two classes: normal and pneumonia.

The input image is preprocessed by converting it to grayscale and resizing it to 224x224 pixels. The preprocessed image is then passed to the model for prediction.

The prediction results are displayed as probabilities for each class. A higher probability indicates a higher confidence in the prediction.

### Tools Used

- HTML
- CSS
- JavaScript
- TensorFlow.js
