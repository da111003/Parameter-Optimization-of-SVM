# Parameter-Optimization-of-SVM
UCS654 : Predictive Analytics using Statistics

## Name : Deepak Aggarwal
  
## Roll No. : 102003483

## Sub-Group : 3CO19

## SVM and Parameter Optimization

Support Vector Machine (SVM) is a popular algorithm used in supervised learning for both classification and regression problems. SVM is commonly used for classification problems in Machine Learning.

To improve the accuracy of SVM, important parameters such as kernel, C, and gamma can be adjusted through a process called hyperparameter tuning. One way to perform hyperparameter tuning is by using GridSearchCV.

In this Python file, a fitness function has been implemented to optimize these parameters for SVM.

## Dataset (Number of Instances: 10129, Number of Attributes: 16)

The project's dataset has been acquired from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

The dataset is intended for the purpose of predicting the exact number of people present in a room, utilizing various non-invasive environmental sensors such as temperature, light, sound, CO2, and PIR. This dataset is categorized as a multi-variable classification dataset.

## Final Result Table

<img width="524" alt="Result_Table" src="https://user-images.githubusercontent.com/79132054/233189666-07d88181-bbee-4e59-aedf-6a2e11907c47.png">


## Convergence Graph

<img width="900" alt="Convergence_Graph" src="https://user-images.githubusercontent.com/79132054/233189731-c8a1acdd-b6a1-471d-93da-a17e73898c18.png">


## Discussion
Based on the provided graph, it appears that the model has been effectively trained and the parameters have been optimized, as evidenced by the minimal difference between the training and cross-validation curves.

Additionally, the graph represents the sample with the highest accuracy, which corresponds to Sample 3 with a 0.97 accuracy score. This sample was achieved using a linear kernel, a nu value of 9.97, and an epsilon value of 6.09.

