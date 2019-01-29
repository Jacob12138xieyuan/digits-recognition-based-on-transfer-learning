# digits-recognition-based-on-transfer-learning

1. The first ipynb file is SVHN data preprocessing, in my case, i downloaded the cropped images dataset which is easier to handle. 

2. The second ipynb file contains a little more data processing as well as two trainnings. First we train on MNIST dataset using a simple CNN, then we freeze the weights of CNN and , but fully connected layer remain trainable, then save the entire model into the "mnist_model" file. After that is another train process on SVHN dataset.
