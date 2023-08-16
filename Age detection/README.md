# The Age Detection model

The project is divided into two notebooks, the first one has the loading up of datasets, sorting into classes. The second notebooks has the code for loading up the dataset and augmentation of image dataset and all other preprocessing techniques and model building and training on GPU.

The images in the datasets are the screengrabs of the actors from various movies of present and past in both Modern-Color codex and Black&white movies, this presents us with a serious problem of non uniform size of the images and non uniform distribution. Adding to this set of difficulties is the organization of the dataset itself, the images are unlabeled and poorly organized into just two directories namely "training" and "testing".

### The images in dataset are:

![image](https://github.com/Ln11211/neural-networks/assets/91385411/6b28f7f6-f55a-43ed-beff-6d2f4cc12ca2)


# Notebook 1 (Data loading and inference):

**View it [here](https://nbviewer.org/github/Ln11211/neural-networks/blob/main/Age%20detection/Bollwood-age-detect-1.ipynb)**

Download it [here](https://github.com/Ln11211/neural-networks/blob/main/Age%20detection/Bollwood-age-detect-1.ipynb)

# Notebook 2(Data preprocessing and Model training):

view it [here](https://nbviewer.org/github/Ln11211/neural-networks/blob/main/Age%20detection/bollywood-age-detect.ipynb)

Download it [here](https://github.com/Ln11211/neural-networks/blob/main/Age%20detection/bollywood-age-detect.ipynb)

# Architecture

The model architecture is fairly simple and leverages Transfer learning with a whooping **1.4 crore parameters**. A VGG16 architecture is fine tuned for this task, the model architecture is:

![image](https://github.com/Ln11211/neural-networks/assets/91385411/564f3357-7e0b-4f75-a2c3-0114d9a0e441)
