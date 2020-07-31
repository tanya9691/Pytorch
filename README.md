# Pytorch
## Classifying images of everyday objects using a neural network<br>
#### The ability to try many different neural network architectures to address a problem is what makes deep learning really powerful, especially compared to shallow learning techniques like linear regression, logistic regression etc.
<br>

![image](https://user-images.githubusercontent.com/55913308/89044943-50919880-d368-11ea-9c95-2f011cc95954.png)
#### Explore the CIFAR10 dataset: https://www.cs.toronto.edu/~kriz/cifar.html<br>
## The CIFAR-10 dataset
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class.<br>
There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images.
The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.
![image](https://user-images.githubusercontent.com/55913308/89045333-f93ff800-d368-11ea-88fa-ab1ace6e4762.png)

#### Set up a training pipeline to train a neural network on a GPU<br>
#### Experiment with different network architectures & hyperparameters
<br>
Find these notebooks useful for reference, as you work through this notebook:<br>

https://jovian.ml/aakashns/04-feedforward-nn<br>
https://jovian.ml/aakashns/fashion-feedforward-minimal<br>
