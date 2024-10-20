#Titanic Survival Prediction with Random Forest Classifier
This project is part of my CodSoft internship, where I worked on predicting the survival of passengers aboard the Titanic using machine learning techniques. The dataset provides information such as passenger class, gender, age, ticket details, and more, and the goal is to predict whether a passenger survived based on these features.

##Project Overview
The project focuses on:

Data Cleaning and Preprocessing: Handling missing values, dropping irrelevant columns, and encoding categorical variables.
Exploratory Data Analysis: Visualizing relationships between features (e.g., survival rates based on gender and class).
Feature Engineering: Using transformations like scaling to improve model performance.
Model Building: Applying a Random Forest Classifier to predict survival.
Model Evaluation: Measuring accuracy, generating a confusion matrix, and producing a classification report.

##Steps Involved
Data Loading: Loaded the Titanic dataset using Pandas.
Data Cleaning:
Imputed missing values in the 'Age' column with the median.
Filled missing 'Embarked' values with the mode.
Dropped irrelevant columns such as 'Name', 'Cabin', 'Ticket', and 'PassengerId'.
Data Transformation:
Label encoded the 'Sex' column and applied one-hot encoding to 'Embarked'.
Scaled features using StandardScaler for better model performance.
Data Visualization: Created count plots to visualize survival rates based on passenger class and gender.
Model Training: Trained a Random Forest Classifier using 100 trees.
Evaluation:
Achieved high accuracy on the test data.
Visualized the confusion matrix using a heatmap.
Generated a detailed classification report.

##Technologies Used
Python: For data manipulation, preprocessing, and model building.
Pandas: For data handling.
Seaborn/Matplotlib: For visualizing the data.
Scikit-learn: For machine learning algorithms and evaluation metrics.

##Results
The model provided accurate predictions of passenger survival and demonstrated the power of Random Forest in classification problems. This project helped deepen my understanding of data preprocessing, feature engineering, and model evaluation techniques.
