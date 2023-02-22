# Working with Modern Neural Network Framework
Designed a neural network using PyTorch that achieves 90% *test* (not training) accuracy on the FashionMNIST dataset. 
  - Some modifications were made on:
      - Architecture
      - Hyperparameters
      - Learning rate, activation function, etc
      - Epochs trained

## Fashion MNIST Dataset: 
- Set of 70k black and white images of clothes
  - 60k training instances
  - 10k test instances
- Labels - one-hot encodings of 10 classes
  - 0 T-shirt/top
  - 1 Trouser
  - 2 Pullover
  - 3 Dress
  - 4 Coat
  - 5 Sandal
  - 6 Shirt
  - 7 Sneaker
  - 8 Bag
  - 9 Ankle boot

![preview img](/Dataset.png)

## The Neural Network fulfills the following: 
- Classify images of clothes to assist in the return process at a shipping facility.
  - People will load clothing items onto a conveyer belt which will bring them to a camera. 
  - The camera will capture the image as a 28x28 grayscale picture, and the neural network should return one of the 10 different classes as a result. 
  - The item will be shipped to its corresponding department.   
- Train the netwrok using a training set of 60,000 pictures of clothes. 
- Test the network againts 10,000 pictures of clothes. 
  - The goal here is to make the network classify images of clothes with at least 90% accuracy to ensure the sorting process is beneficial.

### Stretch goals, for future improvements: 
- Achieve higher accuracy. 
- Design your own neural networks in NumPy! (or similar): If you thought that the forward and backward propagation algorithms were cool or you want to get a deeper understanding of algorithms yourself, you can try to code your own! This is certainly doable but might be slower.

## For more details about the application and the code; checkout bellow: 
[Fashion MNIST Neural Network Code](https://github.com/tinanemati/Fashion_MNIST/blob/main/Fashion_MNIST.ipynb)

## Refrences
[Dense neural network for MNIST](https://colab.research.google.com/drive/1bNahKCtLKZLZWbiC574af7cwAocGiXD4?usp=sharing)

[Dense neural netwrok for CIFAR10](https://colab.research.google.com/drive/1eQVaNZ6JZHS5sM8F7cxGV78tHOYISBtq?usp=sharing)

[Deep neural network for MNIST](https://colab.research.google.com/drive/1WLVZwFSnHb0lt1DQYN5w7B6to9J49brN?usp=sharing)

[Deep neural network for CIFAR10](https://colab.research.google.com/drive/1zyPg7ehPtVdl5wAOiAD2hYWuEXuwO1so?usp=sharing)
