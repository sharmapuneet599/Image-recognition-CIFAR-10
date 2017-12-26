# Image-recognition-CIFAR-10
## CIFAR-10 Dataset

The CIFAR-10 dataset (http://www.cs.toronto.edu/~kriz/cifar.html) is a popular dataset for image classification, collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. It is a labeled subset of the [80 million tiny images](http://people.csail.mit.edu/torralba/tinyimages/) dataset.

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images. The 10 classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

The following 10 classes mentioned above will be classified using Convolutional neural networks. In machine learning, a convolutional neural network (CNN, or ConvNet) is a class of deep, feed-forward artificial neural networks that has successfully been applied to analyzing visual imagery and we will be using keras (deep learning library) to implement this.

## Benchmark model
We will be using Inception-v3 model as our benchmark model. We will apply transfer learning and remove the fully connected layer from its architecture then add some layers according to CIFAR-10 dataset. Here is the link for weights (https://github.com/fchollet/deep-learning-models/releases/download/v0.2/inception_v3_weights_th_dim_ordering_th_kernels.h5).  

## I worked on python 3.6 (ipython notebook) used the following libraries for the project:
- Keras (2.)
- matplotlib
- time
- numpy 
- cv2
- sklearn

### For details read the project report everything about in project is explained in it.
