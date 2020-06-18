# CIFAR-10-
Classifying color images of 10 different categories from keras built-in dataset "CIFAR-10" using Convolutional Neural Network(CNN)

Dataset contains 50,000 - 32 * 32 color training images and 10,000 testing images of 10 different categories which includes Airplane, Car, Ship, Truck, Bird, Cat, Deer, Dog, Frog, and Horse

More information about the dataset is found here : https://www.cs.toronto.edu/~kriz/cifar.html

Steps involved:

1) Load the data 

    a) Tuple unpacking the data into X_train, y_train and X_test, y_test
    
2) Visualize a sample image using matplotlib

3) Data Pre-processing 

    a) Scaling both the train and test images
    
    b) Converting Label values to categorical using OneHotEncoding
    
4) Creating a CNN model

5) Evaluation

