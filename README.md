# Image_Classification_CNN

### Cats - <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/cat.1.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/cat.102.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/cat.11.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/cat.116.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/cat.126.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/cat.21.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/cat.257.jpg' width=100 height=100></img>
### Dogs - <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/dog.10.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/dog.120.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/dog.133.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/dog.461.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/dog.473.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/dog.77.jpg' width=100 height=100> <img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/dog.146.jpg' width=100 height=100></img>

### Overview
Image classification is the process of categorizing and labeling groups of pixels or vectors within an image based on specific rules. Image classification can be accomplished using Convolutional Neural Nets. It takes as input an array of images within a specific catagory and assign learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. Based on this setup, the algorithm learns which class the test images belong to, and can then predict the correct class of future image inputs, and can even measure how accurate the predictions are. The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. 

### Dataset
This dataset was downloaded from the Kaggle platform, it contains images of 2 classes of animals - one being the CAT and another being DOG. There are 4000 images of each cats and dogs. There are test dataset having 1000 images of each cats and dogs and we are expected to assign the correct label to the test images.

### Architecture
Convolutional Neural Network - There are two main parts to a CNN architecture. A convolution tool that separates and identifies the various features of the image for analysis in a process called as Feature Extraction. A fully connected layer that utilizes the output from the convolution process and predicts the class of the image based on the features extracted in previous stages. Below is an architectural diagram of CNN.

<img src='https://github.com/Ruparna25/Image_Classification_CNN/blob/main/Images/CNN_architecture1.jpeg' width=600 height=300></img>

### Design
The images are converted into greyscale images and resized to 200 pixels of width and height of images, since training a CNN of a large image requires a lot of high hardware resources. 
