# Parkinson's Disease Detection

Parkinson's Disease Detection using Machine Learning Algorithms.

# Authors:
•	Sai Teja Karlapudi
•	Sai Saketh Kamabalapally

# Softwares & Environments Required:
•	Python 3.9
•	Jupyter Notebook
•	Numpy
•	Pandas
•	xgboost
•	Matplotlib
•	Scipy & Scikit-Learn
•	sklearn
•	imblearn
• mlens
• statsmodels.api

# Data:
The dataset can be downloaded from here.
https://archive.ics.uci.edu/ml/datasets/parkinsons

# About Project:
The main objective of this project is to build and train the model on the dataset to acquire the highest possible accuracy in detecting Parkinson’s disease. This helps the doctors to improve accuracy in diagnostics using voice recordings which involves less cost and non-invasive testing.

Parkinson’s Disease (PD) is a chronic neurologic condition that affects both motor and non-motor neural circuits. Hypokinetic dysarthria (Speech deterioration) is a common symptom, which often presents early in the disease course.

Dataset consists of multivariate characteristics with 194 instances. It has 23 attributes and no missing values.

Project execution is planned as follows:

• Data Collection
• Data Pre-processing
• Building the model
• Training & Testing the model

# Results:

Accuracy of Individual Models:
<img src="https://user-images.githubusercontent.com/43872050/167534779-04f7212a-a99c-4471-acaf-ec6a05baec67.png" height="400" />

Confusion Matrix Heat Map of KNN Model:
<img src="https://user-images.githubusercontent.com/43872050/167534793-b99c6f02-ea7c-4f61-92f5-b54dd26d8f9f.png" height="400" />

Acuraccy of Models in 5 Fold Cross Validation:
<img src="https://user-images.githubusercontent.com/43872050/167534813-18361720-fbbd-4972-a09f-d12523f8b1bb.png" height="400" />

Ensemble method:
Adda Boost and XG Boost as layer 1 and K Neighbors as layer 2. Testing accuracy of 83.01% is acquired using Ensemble

## Conclusion:

On comparing the results from the various models, we found that Random Forest and Bagging Classification models give best accuracies when 5 Fold cross validation is applied.

**Random Forest and Bagging = 92.45%**


