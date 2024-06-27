DiabetesPrediction-SVM

Project Overview

The DiabetesPrediction-SVM project aims to develop a predictive model using Support Vector Machine (SVM) algorithms for diagnosing diabetes. The model analyzes health-related data from female patients to predict whether a person has diabetes or not.

Dataset

The dataset used includes health attributes such as the number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI (Body Mass Index), diabetes pedigree function, and age. The target variable, 'Outcome', indicates:

0 for non-diabetic individuals and
1 for diabetic individuals

Steps Involved

Importing Dependencies
Libraries such as NumPy, Pandas, and scikit-learn are imported to handle data manipulation, preprocessing, and model evaluation.

Loading and Exploring the Dataset
The dataset is loaded and basic exploratory data analysis (EDA) is conducted to understand its structure and characteristics.


Data Preprocessing
Features and the target variable are separated.
Data standardization is performed to ensure all features have a uniform scale, which enhances model performance.

Splitting the Data
The dataset is split into training and testing sets using stratified sampling to maintain equal proportions of diabetic and non-diabetic cases in both sets.

Training the SVM Model
An SVM classifier with a linear kernel is trained using the training data. SVMs are chosen for their effectiveness in binary classification tasks like diagnosing diabetes.

Model Evaluation
The trained model's performance is evaluated using accuracy metrics. This helps assess how well the model predicts diabetes on unseen data.

Making Predictions
Using the trained model, predictions are made for new data inputs to classify individuals as diabetic or non-diabetic based on their health attributes.
Results

The model achieves approximately 78% accuracy on the training data and 75% accuracy on the testing data. This indicates a reasonably effective prediction capability for identifying diabetes.

Conclusion

This project illustrates the application of SVMs in medical diagnostics, emphasizing the importance of data preprocessing and evaluation in building reliable predictive models for healthcare applications.

