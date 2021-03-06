# Image Classification
 
This Repository is a collection of all image classification projects. 

## [1. Simpsons Character Recognition:](https://github.com/VishnuK11/Image-Classification/tree/main/Simpsons%20Character%20Recognition)
The Simpsons Character Dataset is a collection of 21K images of 42 characters of the Simpsons show. The images concerning the top 20 characters of the dataset are chosen for this project, amounting to 19K images. The model architecture containts 7 blocks of layers. Each block has a one padding layer, a batch normalization layer and about 'K' Conv2d layers for the Kth block. The model performed excellent, with 95% training accuracy, 92% validation accuracy and 95% test accuracy.

## [2. Fashion MNIST:](https://github.com/VishnuK11/Image-Classification/tree/main/Simpsons%20Character%20Recognition)
The Fashion MNIST image classification is a classical image classification excercise. It consists of 10 classes of fashion items in dataset of 60K training images and 10K test images. In this notebook, I've explored a step-by-step approach on the various model architectures starting with a vanilla neural network. The test dataset was divided into validation and test dataset consisting of 2K and 8K images respectively. By looking at the Accuracy - Epoch and Loss-Epoch plots, I have gradually made necessary changes in the  model architecture to get a 2%-3% improvement on the test performance. The final model performed with an accuracy of 92% compared to the inital performance of 89% on the test dataset.
