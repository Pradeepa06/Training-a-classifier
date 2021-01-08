# Training-a-classifier


# Training a 60 minute Blitz using pyTorch

 Using standard python packages that load data into a numpy array. Then you can convert this array into a torch.*Tensor.

For images, packages such as Pillow, OpenCV are useful

For audio, packages such as scipy and librosa

For text, either raw Python or Cython based loading, or NLTK and SpaCy are useful.

Specifically for vision, we have created a package called torchvision, that has data loaders for common datasets such as Imagenet, CIFAR10, MNIST, etc

and data transformers for images, viz., torchvision.datasets and torch.utils.data.DataLoader.

 we will use the CIFAR10 dataset.
 
It has the classes: ‘airplane’, ‘automobile’, ‘bird’, ‘cat’, ‘deer’, ‘dog’, ‘frog’, ‘horse’, ‘ship’, ‘truck’.

The images in CIFAR-10 are of size 3x32x32, i.e. 3-channel color images of 32x32 pixels in size.


# We will do the following steps in order:


1.Load and normalizing the CIFAR10 training and test datasets using torchvision

2.Define a Convolutional Neural Network

3.Define a loss function

4.Train the network on the training data

5.Test the network on the test data

