# Using Transfer Learning and TensorFlow 2.0 to Classify Different Dog Breeds

This is a project that utilizes transfer learning and TensorFlow 2.0 to classify different dog breeds. Transfer learning is a machine learning technique that allows a model to leverage the knowledge learned on one task to another task.


## Dataset
For the dataset, I'm using data from the [Kaggle dog breed identification competition](https://www.kaggle.com/c/dog-breed-identification/overview). It consists of a collection of 10,000+ labeled images of 120 different dog breeds.

## Requirements
To run this project, you will need the following:

* Python 3.6 or later
* TensorFlow 2.0 or later
* Jupyter Notebook

__OR__

* A Google account
* Google Colaboratory: a free Jupyter Notebook environment that runs on Google's cloud servers
* Google Drive: a cloud storage service provided by Google that integrates with Google Colaboratory

There are no additional Python package requirements for this project as Google Colaboratory comes pre-installed with most of the necessary libraries. However, if you need any additional packages, you can install them using the `!pip install` command in the notebook.

## Usage
To run this project, open the Jupyter Notebook file `dogs_indefication.ipynb` and follow the instructions.

## Results
After training the model on the full data training set and validating it on the validation set, we achieved an accuracy of over 90% on the test set.

<img width="933" alt="kaggle_set1" src="https://user-images.githubusercontent.com/55165756/231541121-b7fcd4f7-571c-4401-961d-e2b012511cbd.png">

<img width="887" alt="kaggle_set2" src="https://user-images.githubusercontent.com/55165756/231541139-cf01d599-d871-4d38-a13b-8b645c0934ef.png">


After we make predictions on a test dataset that was provided by Kaggle, we test our model for our chosen images:

<img width="643" alt="custom_set" src="https://user-images.githubusercontent.com/55165756/231541520-4bbc2c61-0d4d-4570-8f73-e5664cc0be5a.png">


## Conclusion
This project demonstrates how transfer learning can be used to classify different dog breeds. By using a pre-trained model and freezing its weights, we were able to build a classifier that achieves high accuracy with a relatively small amount of training data.





