# Object Detection with NN, CNN, and VGG16 on CIFAR-10

## Project Overview

This project implements an object detection model using Neural Networks (NN), Convolutional Neural Networks (CNNs), and the VGG16 architecture, trained on the CIFAR-10 dataset. It includes a simple perceptron model and a more advanced VGG16 transfer learning model to distinguish between different objects in images. A sliding window technique is used to detect objects within a larger image.

## Features

- Image preprocessing and normalization.
- One-hot encoding of labels.
- Implementation of a simple perceptron for baseline performance.
- Advanced object detection using the VGG16 model with transfer learning.
- Sliding window approach for object localization.
- Evaluation of model performance with accuracy metrics.

## Prerequisites

Before running this project, ensure that you have the following:

- Python 3.8 or higher.
- TensorFlow 2.x.
- NumPy, Pandas, Matplotlib, Seaborn for data manipulation and visualization.
- PIL for image file operations.

## Installation

1. Clone this repository to your local machine using:
git clone [https://github.com/CodCodingCode/Object-Detection-with-NN-CNN-VGG16.git

2. Navigate to the cloned directory:
cd Object-Detection-with-NN-CNN-VGG16

3. Enjoy!


## Dataset

The CIFAR-10 dataset is used in this project. It contains 60,000 32x32 color images in 10 different classes. The classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. For the purpose of this project, we focus on two classes: cars and trucks.

## Contributing

We welcome contributions to this project. If you want to contribute, please fork the repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Nathanyan2008p@gmail.com

## Acknowledgments

- The CIFAR-10 dataset maintainers and contributors.
- The TensorFlow team for providing a comprehensive deep learning framework.

