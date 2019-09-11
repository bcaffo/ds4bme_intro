# Introduction to data science syllabus

Class times: MW 3:00PM - 4:15PM

TA time: F 11:00AM - 11:50AM

Class location: Krieger 205

Instructor office hour. MW 2:00PM - 3:00PM Clark 314B.

TA hour location: 

Book: [Goodfellow, Benjio and Courville, Deep Learning](https://www.deeplearningbook.org/) 


# Grading

Quiz Wednesday afternoons

2 projects, dates TBA

Grade is average of project grade and quiz grades

## Lab course

The associated lab course is mandatory.


## Colab ipython notebooks

* [Notebook 1, some basic python and data input and munging](https://colab.research.google.com/drive/1oswpzvkRaphIkoTqXqa244kUWBSJfDw5)
* [Notebook 2, simple classification and evaluation](https://colab.research.google.com/drive/1JzktE6vya812O6lbCy7rzrrt1YCAdIfE)
* [Notebook 3, regression prediction](https://colab.research.google.com/drive/1rWDI6uNhLtwN8KPMPt5mhYaPqDixzWbQ)
* [Notebook 4, regression classification](https://colab.research.google.com/drive/1Yc04O2KNHJ5GBFYE2Krt8cwJeNHwfOMb)

## Hand written notes

* [Directory of hand written notes](https://drive.google.com/drive/folders/1aGS6NeEGFOnJKUdv0p6ASFIrOfQPn22V?usp=sharing)

## Lectures

## Topics and rough organization of lectures
0. Introduction to data science for BME
    1. [Git and github, version control](https://github.com/seankross/the-unix-workbench/blob/master/docs/06-Git-and-GitHub.md)
    2. [Markdown](https://www.markdownguide.org/basic-syntax/)
    3. Exploratory data analysis
    4. [Reproducible research, replication crisis, some relevant links](https://github.com/bcaffo/ds4bme/blob/master/reproducible.md)
    5. Computational topics: python and frameworks.
    6. Example: reading in some MRI Cloud data
    7. Grading and course structure; github classroom.    
1. Introduction to classification and prediction
    1. Classification with one continuous predictor and thresholding
    2. Simple regression prediction through the origin
    3. Loss functions, squared error, cross entropy
    4. Example with voxel data
    5. Computational topics, loading a simple dataset into a python notebook and creating a simple prediction algorithm
2. Linear separable models
    1. Least squares prediction in a linear model
    2. Binary least squares prediction with cross entropy error.
    3. Example
    4. Computational topics, building a linear model in python
3. Simple neural networks
    1. Correspondence between network diagrams and loss functions
    2. Example: fitting XOR with a neural network
    3. Example: linear regression as a one layer
    4. Example: binary logistic regression as a one layer NN
    5. Example with MRI cloud data 
    6. Computational topics: installing pytorch (or TF?), pip or conda, ...
4. Deep neural networks
    1. Fitting and back propagation
    2. Dropout and regularization; bagging
    3. Modern computational issues, GPU computing
    4. Frameworks (TF, pytorch, ...)
    5. Example: handwritten digit classification
    6. Example: siamese network prediction using a deep neural network.
5. Special networks
    1. Convoluational NNs.
    2. Recurrent NNs.
    3. Autoencoders.
    4. Example: cats versus dogs
    5. Example: hand written digits
    6. Example: activity classification ?
6. Evaluation
    1. Overfitting
    2. Evaluation metrics
    3. Generalizability
    4. Missing data
  
