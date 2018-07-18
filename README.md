# CNN-for-Cifar-10
Here we will create a CNN(Convolutional Neural Network) for classifying images on Cifar-10 data-set.

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

Download the dataset from this link:
https://drive.google.com/open?id=1M70PQW1HX_wMFPzpdA3aA9IjlB5ptHMU

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

Here we achieve image classification on CIFAR-10 using tensorflow.

By changing hyperparameters of CNN, we achieve 92% accuracy on training set and 72% accuracy on test set.

#QUICK START GUIDE:

step 
1. Download and extract the data-set and substitute its location for the training and testing data in the code. 
2. Specify the location of the model to save weights values
3. Install the necessary python packages.
4. When training finishes, we have to just execute the main function to get the prediction results. 
