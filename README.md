# Sequential vs CNN for MNIST Number Prediction

## Introduction

This project aims to compare the performance of sequential models and Convolutional Neural Networks (CNNs) for predicting numbers from the MNIST dataset. The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits from 0 to 9.

## Requirements

To run the code, you'll need:

- Python 3.x
- TensorFlow 2.x
- Keras
- Numpy
- Matplotlib

You can install the required Python libraries using pip:

```bash
pip install tensorflow keras numpy matplotlib
```

## Dataset

The MNIST dataset is a standard benchmark dataset in the field of machine learning and computer vision. It consists of 60,000 training images and 10,000 test images. Each image is a 28x28 grayscale image representing a digit from 0 to 9.

## Models

### Sequential Model

The sequential model is a simple linear stack of layers. In this project, we'll build a sequential model consisting of fully connected layers to classify the MNIST digits.

### CNN Model

Convolutional Neural Networks (CNNs) are powerful for image classification tasks. In this project, we'll build a CNN model using convolutional layers and max pooling layers to extract features from the MNIST images.

## Results

After running both scripts, you'll get the accuracy and loss metrics for both the sequential and CNN models on the test dataset. You can compare these metrics to evaluate the performance of each model.

## Conclusion

Based on the results, you can draw conclusions about which model performs better for the MNIST digit classification task: sequential or CNN.

## Contributors

- Pranjali Naik (@PranjaliNaik11)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
