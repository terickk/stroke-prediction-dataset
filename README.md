# Predicting stroke probability

# Abstract
The goal of this project is to use machine learning models to Predict whether a patient is likely to get stroke or not. This project is one of SDAIA T5 Data Science Bootcamp requirements. Data provided by Kaggle.com has been used in this project. I used Jupyter Notebook to run a python code for preparing, cleaning, and visualizing the data. I applied five different models and measure the accuracy.

# Data
The dataset contains 5110 unique records with 12 attributes for each, collecting from 2995 females and 2115 males. The last column contains ‘1’ if the patient had stroke and ‘0’ if he or she hadn’t. A few attributes like age, marriage, and hypertension will be consider in prediction model. The dataset will be divided in three parts:
-	20% for testing.
-	60% for training.
-	20% for validation.

# Algorithms
-	Feature Engineering

o	Substituting the missing values with the mean.
o	Replacing the outlier values with the mode.
o	Visualize the relation between stroke and other features by use pandas crosstab and seaborn heatmap.
o	Convert categorical variables to numbers by LabelEncoder in sklearn.
o	scale values of avg_glucose_level,  bmi, and age by using StandardScaler in sklearn.
o	use SMOTE from imblearn to solve the imbalence data
-	Models

Applied Logistic Regression, Random Forest, Decision Tree, K-nearest neighbors, Naive Bayes, and Naive Bayes. The Random Forest which has the highest accuracy were chosen as the model.
-	Final score for each models

Applied Logistic Regression:  0.786692759295499
Random Forest:  0.910958904109589
Decision Tree:  0.8688845401174168
KNN:  0.8140900195694716
Naive Bayes:  0.8140900195694716
KMeans:  0.8551859099804305

# Tools
-	pandas.
-	numpy.
-	matplotlib.
-	seaborn
-	sklearn.
