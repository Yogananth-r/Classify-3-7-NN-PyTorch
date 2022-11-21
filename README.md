# Classify-3 & 7-NN-PyTorch

- This is a neural network to classify the digits three and seven from an image
Every image that we pass to our neural network is just a bunch of numbers. That is, each of our images has a size of 28×28 which means it has 28 rows and 28 columns, just like a matrix.

- We see each of the digits as a complete image, but to a neural network, it is just a bunch of numbers ranging from 0 to 255.

- We need to download a data set called MNIST (Modified National Institute of Standards and Technology) from the torchvision library of PyTorch.

- So, what we do is simply feed the neural network the images of the digits and their corresponding labels which tell the neural network that this is a three or seven.

- We just write the code to index out only the images with a label of three or seven. Thus, we get a data set of threes and sevens.

- We will create a single layer neural network with sigmoid function.
