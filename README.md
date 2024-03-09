Diabetes Analysis

Overview

This project aims to analyze the Pima Indians Diabetes Dataset using Python and various data analysis techniques. The dataset contains several medical predictor variables and one target variable indicating whether a patient has diabetes. The goal is to predict the onset of diabetes based on these diagnostic measurements.

Dataset Description

The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It includes the following columns:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
Outcome (1 for diabetes, 0 for no diabetes)
Analysis Steps

Data Import and Exploration: The dataset is loaded using pandas, and basic exploratory data analysis (EDA) is performed to understand the structure and summary statistics of the data.
Data Cleaning: Any missing values or inconsistencies in the data are handled to ensure data quality.
Data Visualization: Various visualizations such as histograms, scatter plots, and box plots are created to explore relationships between variables and understand the distribution of data.
Model Building: Logistic Regression model is trained on the data to predict the onset of diabetes based on the available features.
Model Evaluation: The model's performance is evaluated using accuracy, confusion matrix, classification report, and ROC curve analysis.
Feature Importance: Random Forest classifier is utilized to determine the importance of features in predicting diabetes.
Clustering Analysis: K-means clustering is applied to identify distinct clusters within the dataset based on relevant features.
Technologies Used

Python
pandas
NumPy
Matplotlib
Seaborn
scikit-learn
Files

diabetes.csv: The dataset file containing the diabetes data.
DiabetesAnalysis.ipynb: Jupyter Notebook containing the Python code for data analysis.
README.md: This README file providing an overview of the project.
Usage

To run the analysis:

Clone the repository to your local machine.
Open DiabetesAnalysis.ipynb in Jupyter Notebook or any compatible environment.
Execute the cells in the notebook to perform data analysis and visualization.
Author

Avinash Behera
Feel free to reach out for any questions or feedback!
