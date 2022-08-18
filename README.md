# Introduction
Convolutional Neural Networks (CNN), a technique within the broader Deep Learning field, have been a revolutionary force in Computer Vision applications, especially in the past half-decade or so. One main use-case is that of image classification, e.g. scene classification and object detection.

# Project Description
In the paper, Food-101 – Mining Discriminative Components with Random Forests, they introduce the Food-101 dataset. There are 101 different classes of food, with labeled images per class available for supervised training.

# Results
After fine-tuning a pre-trained Google EfficientNetB0 model, I was able to achieve about 97 % accuracy on training dataset and 85% accuracy in testing dataset. For the faster performance, I also used Mixed Precision for training the model.
