# Parameter-Optimization-of-SVM
UCS654 : Predictive Analytics using Statistics

## Written By
Name : Deepak Aggarwal
  
Roll No. : 102003483

Sub-Group : 3CO19

## SVM and Parameter Optimization

Support Vector Machine (SVM) is a popular algorithm used in supervised learning for both classification and regression problems. SVM is commonly used for classification problems in Machine Learning.

To improve the accuracy of SVM, important parameters such as kernel, C, and gamma can be adjusted through a process called hyperparameter tuning. One way to perform hyperparameter tuning is by using GridSearchCV.

In this Python file, a fitness function has been implemented to optimize these parameters for SVM.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 10129

Number of Attributes: 16

## Final Result Table

<img width="524" alt="Result_Table" src="https://user-images.githubusercontent.com/79132054/233189666-07d88181-bbee-4e59-aedf-6a2e11907c47.png">


## Convergence Graph

<img width="900" alt="Convergence_Graph" src="https://user-images.githubusercontent.com/79132054/233189731-c8a1acdd-b6a1-471d-93da-a17e73898c18.png">


## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.


