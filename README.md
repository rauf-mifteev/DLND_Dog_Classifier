# Udacity Deep Learning Nanodedree Dog Breed Clissifier

This is dog breed classifier project for Udacity's Deep Learning Nanodegree program. In this project, I develop code for an image classifier in **Jupiter Notebook** using **Keras** over **Tensorflow**. This code must be able to:

* Detect whether an image contains a dog or human, and distinguish between the two.
* If given an image of a dog, the model predicts the its breed with at least 60% accuracy. Random chance is less than 1% since there are 133 dog breeds (classes) in the dataset.
* If given an image of a human, the model identifies the dog breeds the person most resembles.

After exploring different CNN models, including **VGG**, **ResNet**, **InceptionV3**, and **Xception**, I chose Xception model because it showed the best test accuracy. Using **learning transfer** I added and trained two final layers on top of pretrained CNN to do the final classification of dog breeds.

## Prerequisites
The code is in a Jupyter Notebook. You can install Jupyter Notebook by installing [Anaconda](https://jupyter.readthedocs.io/en/latest/install.html#installing-jupyter-using-anaconda-and-conda) or with pip

`pip3 install jupyter`

## Installing
Clone this repository

`git clone https://github.com/rauf-mifteev/DLND_Dog_Classifier.git`

## Run the Code
Navigate to the cloned directories location and start jupyter notebook with dlnd_tv_script_generation.ipynb

`jupyter notebook dog_app.ipynb`
