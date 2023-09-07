# Handwritten Alphabet Recognition using Convolutional Neural Networks (CNN)

This repository contains a Python script that demonstrates the use of Convolutional Neural Networks (CNN) for recognizing handwritten alphabets. The script uses the Keras library with TensorFlow backend to create and train a CNN model.

## Prerequisites

Before running the code, ensure that you have the following libraries installed:

- Matplotlib
- OpenCV (cv2)
- Numpy
- Keras
- Pandas
- Scikit-Learn


You can install these libraries using pip:

```bash
pip install matplotlib opencv-python numpy keras pandas scikit-learn
```

## Usage

1. Clone this repository to your local machine.

2. Ensure you have also downloaded the provided dataset or your own data file that contains handwritten alphabet images. The provided data is in a format where each row corresponds to an image, and the first column is the label for that image. Several such images(37k+ rows) are available in the provided dataset.

3. Run the script by executing it in your Python environment.

4. The script will perform the following tasks:

   - Load and preprocess the data.
   - Visualize the distribution of alphabet labels in the dataset.
   - Display a sample of shuffled images from the dataset.
   - Define and train a CNN model for alphabet recognition.
   - Display training and validation accuracy/loss curves.
   - Make predictions on sample images.
   - Perform alphabet recognition on a user-provided image (`x.png`).

## Description

- The script starts by importing the necessary libraries and loading the dataset. It then splits the data into training and testing sets.

- It preprocesses the data by reshaping the images and one-hot encoding the labels.

- The distribution of alphabet labels in the dataset is visualized using a bar chart.

- A sample of shuffled images is displayed to provide an overview of the dataset.

- A CNN model is defined and trained using the training data. The model architecture consists of convolutional layers, max-pooling layers, and dense layers.

- The training and validation accuracy/loss curves are plotted to evaluate model performance.

- The script also demonstrates alphabet recognition by making predictions on sample images from the testing dataset.

- Finally, the script performs alphabet recognition on a user-provided image (`x.png`) and displays the predicted alphabet.

## Files

- `handwritten_alphabet_recognition.txt`: The main Python script containing the code for alphabet recognition.
- `a.png`: An example image for alphabet recognition.

## Acknowledgments

This code is for educational purposes and demonstrates how to build a simple CNN model for handwritten alphabet recognition.
