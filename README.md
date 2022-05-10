# Parkinson's-Disease-Detection

Parkinson's Disease Detection using Machine Learning Algorithms.

# Authors
•	Sai Teja Karlapudi
•	Sai Saketh Kamabalapally

# Softwares & Environments Required
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

# Data
The dataset can be downloaded from here.
https://archive.ics.uci.edu/ml/datasets/parkinsons

# About Project
The main objective of this project is to build and train the model on the dataset to acquire the highest possible accuracy in detecting Parkinson’s disease. This helps the doctors to improve accuracy in diagnostics using voice recordings which involves less cost and non-invasive testing.

Parkinson’s Disease (PD) is a chronic neurologic condition that affects both motor and non-motor neural circuits. Hypokinetic dysarthria (Speech deterioration) is a common symptom, which often presents early in the disease course.

Dataset consists of multivariate characteristics with 194 instances. It has 23 attributes and no missing values.

Project execution is planned as follows:

• Data Collection
• Data Pre-processing
• Building the model
• Training & Testing the model

# Results

Accuracy of Individual Models:
<img src="https://user-images.githubusercontent.com/43872050/167531447-620c165b-4d17-44d1-90c8-0635531f7856.png" height="400" />

Confusion Matrix Heat Map of KNN Model:
<img src="https://user-images.githubusercontent.com/43872050/167531530-c3d28659-cac4-44a4-ab61-c33a7fb51304.png" height="400" />

Acuraccy of Models in 5 Fold Cross Validation:
<img src="https://user-images.githubusercontent.com/43872050/167531666-362c60ce-2195-4f93-bd4a-512c7ecf81ff.png" height="400" />

Ensemble method:
Adda Boost and XG Boost as layer 1 and K Neighbors as layer 2. Testing accuracy of 83.01% is acquired using Ensemble

## Metrics



