# Dog Breed Clissifier Project for Udacity Deep Learning Nanodedree 

## Project overview
This is dog breed classifier project for Udacity's Deep Learning Nanodegree program. In this project, I build and train **Convolutional Neural Network (CNN)** as image classifier in **Jupiter Notebook** using **Keras** over **Tensorflow**. This code must be able to:

* Detect whether an image contains a dog or human, and distinguish between the two.
* If given an image of a dog, the model predicts the its breed with at least 60% accuracy. Random chance is less than 1% since there are 133 dog breeds (classes) in the dataset.
* If given an image of a human, the model identifies the dog breeds the person most resembles.

After exploring different CNN architectures, including pretrained **VGG-19**, **ResNet-50**, **InceptionV3**, and **Xception**, I chose Xception model because it showed the best test accuracy. Using **learning transfer** I added and trained two final layers on top of pretrained CNN to do the final classification of dog breeds.

## Prerequisites
The code is **Python** in a **Jupyter Notebook** and it uses:

* [Keras](https://keras.io/)
* [Tensorflow](https://www.tensorflow.org/)
* [SciKit-learn](https://scikit-learn.org/stable/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [NumPy](http://www.numpy.org/)

You can install everything you need to run this project with [Anaconda](https://www.anaconda.com/).

## Installing
Clone this repository

`git clone https://github.com/rauf-mifteev/DLND_Dog_Classifier.git`

## Run the Code
Navigate to the cloned directories location and start jupyter notebook with dlnd_tv_script_generation.ipynb

`jupyter notebook dog_app.ipynb`
