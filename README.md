# Dog Breed Classifier

## Motivation

This project is to develop a function that takes an image as input and classifies the image as either a human or a dog and then classify the breed of the dog. If the image is neither human nor dog, it throws an error message. Following objectives are tackled in the analysis-

1. How to detect human faces in the given image?
2. How to detect dogs in the given image?
3. How to classify the dog breed in the given image by Convolutional Neural Network (CNN)?
4. How to classify the dog breed in the given image by Transfer learning?

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

Python: 3.7.1

Packages: numpy, keras, matplotlib, cv2, sklearn


### Installing

You can install python from this [link](https://www.python.org/downloads/release/python-371/).

Packages can be installed using the 'requirements.txt' that is available in the repository.

```python
pip install -r requirements.txt
```

### Files used:

* dog_app.ipynb - notebook containing analysis
* dog_app.html - the html version of the jupyter notebook
* extract_bottleneck_features.py - functions to extract bottleneck features from models
* haarcascades/ - haar cascade definition file for face recognition
* requirements/ - requirements files

### Summary

In this project, we learned how to develop a convolutional neural network to perform image classification. Various approaches were tried to develop the model that classifies the breed of the dog and we learned that the transfer learning model performed better than the model that was developed from scratch. The transfer learning model had more than 80% accuracy on test data. However, there is scope for improvement of the performance of the model. We can try out the following:

* Add more layers to the transfer learning model to increase the complexity
* Data augmentation to avoid overfitting
* Increase the number of data points used to develop the model
* Increase the number of epochs used to develop the model

The analysis is summarized in this blog [post](https://suhaskaranth2008.medium.com/dog-breed-classifier-image-classification-using-cnn-af2bb97314b).

## Licensing, Authors, Acknowledgements

The data and main parts of the code was made available by Udacity and you can view the it [here](https://github.com/udacity/dog-project). I have to acknowledge Stackoverflow community as they rescued me from the errors and bugs faced during the analysis.

Please feel free to use my code for your purposes.
