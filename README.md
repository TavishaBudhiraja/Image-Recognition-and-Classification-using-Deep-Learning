# Image Recognition and Classification using Deep Learning

## Overview

This project is based on **image recognition and classification using deep learning**.
A Convolutional Neural Network (CNN) model is built using **TensorFlow and Keras** to classify images from the **CIFAR-10 dataset**.
The CIFAR-10 dataset contains 60,000 color images of size 32x32 pixels across 10 different classes.

## Objective

The main objective of this project is to build a deep learning model that can recognize and classify images into different categories using CNN.
The model is trained and tested on the CIFAR-10 dataset.

## Classes in the Dataset

The CIFAR-10 dataset contains the following 10 image classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The project uses the **CIFAR-10 dataset**, which is available directly through TensorFlow/Keras datasets.

The dataset contains:

- 50,000 training images
- 10,000 testing images
- 10 image categories
- Image size: 32x32 pixels
- Color images with 3 channels

## Project Workflow

1. Installed and imported the required libraries
2. Loaded the CIFAR-10 dataset
3. Normalized image pixel values between 0 and 1
4. Visualized sample training images
5. Built a CNN model using TensorFlow/Keras
6. Trained the model for 10 epochs
7. Plotted training and validation accuracy
8. Evaluated the model on test data
9. Generated predictions
10. Created a confusion matrix
11. Printed the classification report

## CNN Model Architecture

The CNN model includes:

- Convolutional layers for feature extraction
- Max pooling layers for reducing image dimensions
- Flatten layer to convert feature maps into a 1D vector
- Dense layers for classification
- Output layer with 10 units for the 10 CIFAR-10 classes

## Results

The model was trained for 10 epochs and tested on the CIFAR-10 test dataset.

The model achieved approximately **71% test accuracy**.

## Project Demo

A working demo video of this project is available here:

https://drive.google.com/file/d/1t-TubKcCBtsYb7cvHYJLLOKwwMzSuh0Z/view?usp=drivesdk

## How to Run This Project

1. Download this repository.
2. Open the notebook file in **Google Colab**.
3. Run all notebook cells from top to bottom.
4. The CIFAR-10 dataset will be loaded automatically using TensorFlow/Keras.

## Files in This Repository

```text
image-recognition-classification/
│
├── README.md
└── Tavisha_Project.ipynb
```

## Challenges Faced

Some challenges faced during this project were:

- Understanding how CNN layers work
- Learning TensorFlow and Keras syntax
- Interpreting validation accuracy changes during training
- Creating and understanding the confusion matrix

## How These Challenges Were Solved

These challenges were handled by:

- Starting with a simple CNN model
- Understanding each layer step by step
- Using accuracy graphs to check model learning
- Using confusion matrix and classification report for performance analysis

## Future Improvements

This project can be improved further by:

- Using data augmentation
- Adding dropout layers to reduce overfitting
- Training for more epochs
- Trying transfer learning with pretrained models such as ResNet or MobileNet
- Improving accuracy using hyperparameter tuning

## Conclusion

This project helped in understanding the complete deep learning workflow for image classification.

A CNN model was successfully built, trained, tested, and evaluated using the CIFAR-10 dataset.

## Author

Tavisha Budhiraja
