# MNIST Handwritten Digit Recognition

## Description
This project demonstrates the development of a convolutional neural network (CNN) to recognize handwritten digits using the MNIST dataset. The dataset is loaded from custom directories containing grayscale images for training and testing. The dataset used in this project was downloaded from Kaggle. The model is trained to achieve high accuracy in digit classification.

## Features
- Custom dataset loading and preprocessing using TensorFlow.
- Partitioning of the training set into training and validation subsets.
- Data augmentation techniques for enhanced model generalization.
- Implementation of a CNN model with layers for resizing, rescaling, convolution, and pooling.
- Training and evaluation of the model with accuracy and loss visualization.

## Installation
### Prerequisites
- Python 2.x
- Required libraries:
  - TensorFlow
  - NumPy
  - Matplotlib

Install dependencies:
```bash
pip install tensorflow numpy matplotlib
```

## Usage
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Ensure your dataset is organized in the following structure:
   ```
   mnist_png/
       training/
           0/
           1/
           ...
           9/
       testing/
           0/
           1/
           ...
           9/
   ```
3. Run the training script:
   ```bash
   python train.py
   ```
4. View training and validation metrics:
   ```bash
   python plot_metrics.py
   ```

## Dataset
The MNIST dataset is expected to be in PNG format, organized into `training` and `testing` directories with subdirectories for each digit class (0-9). If you don't have the dataset, you can download it from Kaggle (https://www.kaggle.com/datasets/hojjatk/mnist-dataset).

## Results
- Model Accuracy: 97% (Training), 99% (Validation)


## Acknowledgments
- [Kaggle](https://www.kaggle.com/)
- [TensorFlow Documentation](https://www.tensorflow.org/)

