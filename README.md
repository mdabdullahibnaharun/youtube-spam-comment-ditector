# Youtube-Spam-Comment-Detector
Youtube Spam Comment Detector using ML.


### Abstract
We know that YouTube has emerged as the most popular website for sharing and watching 
video content. However, such success has also attracted malicious users, whose goal is to self-promote their videos or spread viruses and malware. Therefore, it is very important to find ways to identify and report these videos & comments.
### Objective
The objective of this project is to create a web-app using python(Flask). This project will be build 
using python modules like Numpy, Flask, SkLearn, Mathplotlib... etc.
In this project, the user has to give youtube comment “predict” button. It will show the result 
below. If the user clicks on the “reload” button, then it will reload the app.
### Prerequisites
 1.Familiarity with Python
 2.Working knowledge of Naive-bayes algorithm.


To build this project we will use the basic concept of python and libraries

A)NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical 
functions to operate on these

B) pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for 
manipulating numerical tables and time series.

C) Scikit-learn is a free software machine learning library for the Python programming language. 
It features various classification, regression and clustering algorithms including support vector 
machines, ...etc.

E) Matplotlib is a plotting library for the Python programming language and its numerical 
mathematics extension NumPy. It provides an object-oriented API for embedding plots into 
applications using general-purpose GUI toolkits like Tkinter, wxPython


To install the libraries we can use pip installer from the command line:
  1) pip install numpy
  2) pip install pandas
  3) pip install sklearn
  4) pip install matplotlib
  
###### Examples
![image](https://user-images.githubusercontent.com/60839928/129749027-c5b332d8-b873-42e4-b2db-bd2da7ddc24f.png)

### THE DATA SET
The dataset is pretty straightforward, it contains 2,000+ comments from popular Youtube videos, The dataset is formatted in a way where each row has a comment followed by a value marked as 1 or 0 for spam or not spam,
The dataset can be downloaded from this website --
https://www.kaggle.com/goneee/youtube-spam-classifiedcomments

#### Project Structure:
Let’s check the steps to build This project using Python
•	Import modules dataset
•	Preprocessing
•	Feature Selection
•	Feature Extraction and Feature Engineering
•	Analyzer and apply algorithm
•	Model Building
•	Predict & Output
##### Implemented Software: 
	Language: Python 3.9.
	IDE:Jupyter Note Book / Google-Colab
	
#### System Diagram

![image](https://user-images.githubusercontent.com/60839928/129749793-5ed8260e-0962-405f-a013-e779e95b5d7b.png)

#### Algorithm (naive bayes)

![image](https://user-images.githubusercontent.com/60839928/129827928-799c790d-c78a-42ee-bbcf-7db882a2a4ef.png)


### Output
![image](https://user-images.githubusercontent.com/60839928/162562207-fd2db8ba-dea0-4825-9683-3b030a3843e7.png)


#### Application Source Code: 

Google-Colab link: 
https://colab.research.google.com/drive/1t1ztDEDjKgwmIiwQ4uqB9IjsvZHC4Flu?usp=sharing

#### Challenges Faced:
Faced error Dataset. Faced problem in Algorithms and Some Little bugs.

#### Outcome
The outcome of this project is a simple application all people can use to check spam comments.

### Conclusion:
This was a great experience doing this project. With these steps, we have successfully created a Data mining. For classifying the YouTube comments as spam and not spam (ham) there are various techniques used. This approach has been tested with real-time YouTube comments and given an overall outcome which is 96% accurate. This approach has been tested with real-time YouTube comments and given an overall outcome which is more accurate. we used popular libraries to rendering datasets and also learned about basics of Machine learning. In this way, successfully created our youtube spam comment detector python project. The challenges we faced and the learning that will come in great help in the future. Hope you enjoyed it.

Thank You. 😊

