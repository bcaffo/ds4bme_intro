# Introduction to data science syllabus

* Instructors: Brian Caffo, Rai Winslow
* Meeting time: Monday / Wednesday 3:00PM - 4:15PM (see below)
* Office hours
  * TA office hours Friday 11:00AM - 11:50AM (see
  * Instructor office hours given over slack
* Labs
* Class location : online, asyncrhonous

Books: 

* [Regression Models](https://leanpub.com/regmods)
* [Goodfellow, Benjio and Courville, Deep Learning](https://www.deeplearningbook.org/) 

# Projects 
The projects are in an ipython notebook [here](https://colab.research.google.com/drive/1uHsNQUcCzsGSjbNy2ypf1XqGceDzyFIN?usp=sharing)

# Grading

Weekly projects counted equally.

## Lab course

The associated lab course is mandatory.

## Colab ipython notebooks

* [Notebook 1, some basic python and data input and munging](https://colab.research.google.com/drive/1oswpzvkRaphIkoTqXqa244kUWBSJfDw5)
* [Notebook 2, simple classification and evaluation](https://colab.research.google.com/drive/1JzktE6vya812O6lbCy7rzrrt1YCAdIfE)
* [Notebook 3, regression prediction](https://colab.research.google.com/drive/1rWDI6uNhLtwN8KPMPt5mhYaPqDixzWbQ)
* [Notebook 4, regression classification](https://colab.research.google.com/drive/1Yc04O2KNHJ5GBFYE2Krt8cwJeNHwfOMb)

## Hand written notes

I'll put a link to handwritten notes from the lectures  here

## Class delivery
This class will be delivered via recorded lectures. Instructor office
hours will be held during a subset of course times, as well as others
to accomodate foreign students in different time zones. Course
communication will be held over slack. Invites to the slack group will
be sent over email.

* Recorded lectures (links will be posted here as well as the slack website)
* Slack discussions
* Live instructor office hours
* Live TA office hours
* Weekly projects to be handed in over github classroom
* This github course site

## Lectures

## Class intstruction schedule and due dates

```
* Date , Instr, Due
* 8/31 , Brian, 
* 9/2  , Brian,
* 9/7  , Off  ,  
* 9/9  , Brian, Project 1 (note delayed due date)
* 9/14 , Brian, Project 2
* 9/16 , Brian, 
* 9/21 , Brian, Project 3
* 9/23 , Brian,
* 9/28 , Brian, Project 4
* 9/30 , Brian, 
* 10/5 , Rai  , Project 5
* 10/7 , Rai  ,
* 10/12, Rai  , Project 6
* 10/14, Rai  ,
* 10/19, Rai  , Project 7
* 10/21, Rai  ,
```

## Software / websites
* [Google colab](https://colab.research.google.com/notebooks/intro.ipynb) we'll use colab to demonstrate some basics
* [Azure notebooks](https://notebooks.azure.com/) we'll use this to demonstrate ipython notebooks
* [Anaconda](https://www.anaconda.com/) For installing python, spyder and ipython notebooks locally
* [git](https://git-scm.com/) Comes with most unix-like systems pre installed. If using Windows, install git
* [github](www.github.com)
  

## Topics
0. Introduction to data science for BME
    1. Git, Github
    0. Google Colab
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
  
