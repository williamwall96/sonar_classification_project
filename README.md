# sonar_classification_project
Supervised Machine Learning project for classifying sonar returns as mines or rocks.

The primary goal of this project is to develop a Supervised Machine Learning model that can classify sonar returns as either a mine (M) or a rock (R). This is a binary classification problem with imbalanced classes, as the distribution of mines and rocks is not equal. The machine learning model should be trained to maximize accuracy and recall, with a special emphasis on minimizing false negatives, which could lead to potentially hazardous situations if mines are misclassified as rocks.

## Data

There are 208 observations with 60 input variables and 1 output variable. The variable names are as follows:

Sonar returns at different angles
…
Class (M for mine and R for rock)

Data was retrieved from "All Datastets for Practiving ML" on Kaggle, authored by koustubhk.

The dataset used is the "Class_Sonar.csv"

Direct Link - https://www.kaggle.com/datasets/kkhandekar/all-datasets-for-practicing-ml

## Data Cleaning

The data was left as is in order to allow EDA to determine classification importance for each Angle.
