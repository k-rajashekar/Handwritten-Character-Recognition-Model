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

## Dataset

Download the handwritten alphabet dataset from the following link:

(https://drive.google.com/file/d/1rhYQyz2rnD0xolCFmeJdjEV7gtjjdCsU/view?usp=sharing)

Place the downloaded dataset in the root directory of this project.

## Usage

1. Clone this repository to your local machine.

2. Ensure you have the necessary dataset or data file named `data` that contains handwritten alphabet images. The data should be in a format where each row corresponds to an image, and the first column is the label for that image.

3. Run the script by executing it in your Python environment.

4. The script will perform the following tasks:

   - Load and preprocess the data.
   - Visualize the distribution of alphabet labels in the dataset.
   - Display a sample of shuffled images from the dataset.
   - Define and train a CNN model for alphabet recognition.
   - Display training and validation accuracy/loss curves.
   - Make predictions on sample images.
   - Perform alphabet recognition on a user-provided image (`yy.png`).

## Description

- The script starts by importing the necessary libraries and loading the dataset. It then splits the data into training and testing sets.

- It preprocesses the data by reshaping the images and one-hot encoding the labels.

- The distribution of alphabet labels in the dataset is visualized using a bar chart.

- A sample of shuffled images is displayed to provide an overview of the dataset.

- A CNN model is defined and trained using the training data. The model architecture consists of convolutional layers, max-pooling layers, and dense layers.

- The training and validation accuracy/loss curves are plotted to evaluate model performance.

- The script also demonstrates alphabet recognition by making predictions on sample images from the testing dataset.

- Finally, the script performs alphabet recognition on a user-provided image (`yy.png`) and displays the predicted alphabet.

## Files

- `Handwritten_textfile.txt`: The main Python script containing the code for alphabet recognition.
- `dd.png`: An example image for alphabet recognition.

## Acknowledgments

This code is for educational purposes and demonstrates how to build a simple CNN model for handwritten alphabet recognition. The dataset used in this code is provided with a google drive link and should be downloaded to run this code.
