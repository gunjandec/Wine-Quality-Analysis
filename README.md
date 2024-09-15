# Wine-Quality-Analysis
This project uses machine learning algorithms to predict the quality of wine based on its chemical properties. The dataset includes various physicochemical features such as acidity, sugar content, and alcohol levels, which are used to classify wines into different quality levels.

## Project Overview
The goal of this project is to build a predictive model that accurately classifies wine quality, helping winemakers and analysts to assess wine based on measurable characteristics.

## Dataset
The dataset used in this project is the Wine Quality Dataset, which contains 1,599 records of red wine samples and 12 attributes, including:

Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Free Sulfur Dioxide
Total Sulfur Dioxide
Density
pH
Sulphates
Alcohol
Quality (target variable)
Key Steps in the Project
## Data Cleaning:

Removed duplicate rows to ensure clean and reliable data for modeling.
No duplicate columns were found.
## Feature Engineering:

Standardized features using StandardScaler for models sensitive to feature scaling (e.g., Logistic Regression, K-Nearest Neighbors).
## Modeling:

Applied multiple machine learning algorithms:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
Evaluated models based on accuracy.
Evaluation:

Used accuracy score to compare model performances.
Random Forest achieved the highest accuracy, followed by Decision Tree and KNN.
## Results
The Random Forest Classifier achieved the best performance in predicting wine quality, with an accuracy of XX%.

## Conclusion
This project demonstrates the power of machine learning in predicting the quality of wine based on measurable chemical properties. It also emphasizes the importance of data preprocessing, such as handling duplicates and scaling, in improving model performance.
