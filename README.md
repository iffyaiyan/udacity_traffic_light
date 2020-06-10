# udacity_traffic_light


The Project
---
The goals / steps of this project are the following:
* Load the data set
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report

### Dependencies
This lab requires:

* [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)

The lab environment can be created with CarND Term1 Starter Kit. Click [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) for the details.

### Dataset and Repository

1. Download the data set. The classroom has a link to the data set in the "Project Instructions" content. This is a pickled dataset in which we've already resized the images to 32x32. It contains a training, validation and test set.
2. Clone the project, which contains the Ipython notebook and the writeup template.
```sh
git clone https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project
cd CarND-Traffic-Sign-Classifier-Project
jupyter notebook Traffic_Sign_Classifier.ipynb
```

### Writeup / README

### Step O: Load The Data
#### Here I used the link given to load training_file, validation_file and testing_file

### Step 1 Data Set Summary & Exploration

#### 1a. Here First I did the necessary imports and used Python, Pandas or numpy methods rather than hard coding the results
I got the following
* The size of training set is 34799
* The size of test set is 12630
* The shape of a traffic sign image is (32, 32, 3)
* The number of unique classes/labels in the data set is 43

#### 1b. Include an exploratory visualization of the dataset
It pulls in a random set of eight images and labels them with the correct names in reference with the csv file to their respective id's

### Step2 Design and Test a Model Architecture
#### 2a. Pre-process the Data Set (normalization, grayscale, etc.)
I did preprocessing to obtain information about normalized and original images

#### 2b. Model Architecture
* In this I used all the methodology from the lesson itself as it is with some modification wherever required.
* I got Vaidation accuracy of of 99.0%

### Step 3 Test a Model on New Images
#### 3a. Load and Output The Images
#### 3b. Predict the Sign Type for Each Image
#### 3c. Analyze Performance
#### 3d. Output Top 5 Softmax Probabilities For Each Image Found on the Web
