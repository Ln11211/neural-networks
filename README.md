## Neural-Networks
A collection of Neural networks and NN models trained by me while I learn deep learning :)

# 1)Custom Multiclass classifier
This interactive notebook is a quick wakthrough of the ML workflow of loading up an image dataset and performing a multiclass classification. The dataset is the famous CIFAR_10 dataset having 10 classes. The model that I built is a simple custom model with couple of Convolution blocks and MaxPooling box with a FC dense layer as the classifier head. THe dataset comes preprocessed from the TF Hub datasets but this is a good introduction notebook for beginners.

# 2)Garment recognition model
Another multiclass classifier trained on the Fashion MNIST dataset with a deeper Neural network and more convolution blocks with an aim to understand if the depth of a model increases the accuracy of the classifier. This is a direct improvement over the Cifar model with evidently deeper architecture and more parameters.

# 3) Indian Age recognition model
 A Deep computer vision model with the ability to identify the age of an Indian and classify them into one among the three age groups- Young, Old, Middle.
The dataset I used for this Project is The Indian Movie Face database (IMFDB) by Shankar shetty et-al.[https://ieeexplore.ieee.org/document/6776225]

The images in the datasets are the screengrabs of the actors from various movies of present and past in both Modern-Color codex and Black&white movies, this presents us with a serious problem of non uniform size of the images and non uniform distribution. Adding to this set of difficulties is the organisation of the dataset itself, the iamges are unlabelled and poorly organized into just two directories namely "training" and "testing".

The training directory comes with an additional excel file containing the class labels for all the individual images.

I first replaced the images and sorted them into thier respective classes using the Pandas library, OS library and Python's PILLOW.

The project is divided into two notebooks, the first one has the loading up of datasets, sorting into classes.
The second notebooks has the code for loading up the dataset and augmentation of image dataset and all other preprocessing techniques and model building and training on GPU.

The model inference is then performed in the third dataset.
