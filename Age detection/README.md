
# Indian Age recognition
 A Deep computer vision model with the ability to identify the age of an Indian from the photograph and classify them into one among the three age groups- Young, Old, Middle.
 
The dataset I used for this Project is The Indian Movie Face database (IMFDB) by Shankar shetty et-al.[https://ieeexplore.ieee.org/document/6776225]

The images in the datasets are the screengrabs of the actors from various movies of present and past in both Modern-Color codex and Black&white movies, this presents us with a serious problem of non uniform size of the images and non uniform distribution. Adding to this set of difficulties is the organisation of the dataset itself, the iamges are unlabelled and poorly organized into just two directories namely "training" and "testing".

The training directory comes with an additional excel file containing the class labels for all the individual images.

I first replaced the images and sorted them into thier respective classes using the Pandas library, OS library and Python's PILLOW.

The project is divided into two notebooks, the first one has the loading up of datasets, sorting into classes.
The second notebooks has the code for loading up the dataset and augmentation of image dataset and all other preprocessing techniques and model building and training on GPU.

The model inference is then performed in the third dataset.
