# CNN-for-Fashion-Classification
Deep Learning CNN for Fashion Clothing Classification

![alt text](https://cse.unl.edu/~sscott/teach/Classes/cse496S19/hw/01/FashionMNIST.png)

Image Classification is one of the most popular tasks in deep learning where we are given a particular image and the model has to predict the class of the image. This repo trains a Convolutional Neural Network (CNN) with Keras on the Fashion MNIST dataset to classify fashion images and categories.

<b>The dataset consists of:</b>

- 60,000 training examples
- 10,000 testing examples
- 28×28 grayscale images
- 10 classes

<b>These ten classes are:</b>
- T-shirt/top
- Trouser/pants
- Pullover shirt
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

The dataset can be downloaded from [here](https://www.kaggle.com/zalando-research/fashionmnist) or you can clone the official Fashion MNIST GitHub [repo](https://github.com/zalandoresearch/fashion-mnist), the dataset appears under data/fashion. We gonna use the 60,000 images to train the CNN and the 10,000 images to evaluate how accurately the network learned to classify images.
