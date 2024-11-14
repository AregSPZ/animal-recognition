# Animal Recognition

Leveraging transfer learning with EfficientNet to classify images of 50 animal species.


# Overview

The project involves using transfer learning with EfficientNetB0 to classify images of 50 different animal species. The number of classes is 49 (tortoises and turtles are merged together), which makes it a multiclass classification. The model's task is to classify each image under a single label. The number of images per class ranges from 1300 to 4500, the dataset as a whole contains 67000 images.

# Frameworks Used

TensorFlow: An open-source platform for machine learning.

Keras: A high-level neural networks API, written in Python and capable of running on top of TensorFlow.


# Models Used

EfficientNetB0: A state-of-the-art convolutional neural network architecture used for image classification tasks.

Transfer Learning: Using a pre-trained model and fine-tuning it on the animal species dataset.

# Results

Over 0.98 F1 macro score and 0.15 cross entropy loss on test set.

# Links

[Model (Kaggle)](https://github.com/AregSP/animal-recognition/edit/main/README.md)

[Notebook (Kaggle)](https://www.kaggle.com/code/quant27/animal-recognition)
