# Stroke-Prediction
Stroke is one of the major causes of deaths in the world. The aim of this project is to predict whether a patient is likely to get stroke based on several input factors such as age, gender, hypertension, heart disease, bmi, marital status, residence type, smoking status and glucose level. The dataset for this project has been taken from Kaggle.
After some EDA on the data, it is observed that the 'bmi' column consists of most missing values. Simple Imputer is used to handle the missing values.
The data was also imbalanced. For managing the imbalanced data, oversampling is used. For this purpose SMOTE is used. The highest accuracy on this dataset is achieved using the Random Forest Classifier.
