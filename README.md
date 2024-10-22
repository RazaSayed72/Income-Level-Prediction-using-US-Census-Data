# Income-Level-Prediction-using-US-Census-Data
Predict whether an individual earns more than $50K annually using demographic data from the 1994 US Census. The dataset includes features like age, education, and occupation. Various machine learning models are implemented to optimize prediction accuracy and derive insights into income-related factors.

# Income Level Prediction

## Project Overview
This project focuses on predicting whether an individual earns more than $50K annually using demographic data from the 1994 US Census. By leveraging various machine learning algorithms, we aim to build a model that accurately classifies individuals based on income level.

## Dataset
The dataset used for this project was extracted from the 1994 Census database and contains information on individuals such as:
- Age
- Workclass
- Education level
- Marital status
- Occupation
- Relationship
- Race and gender
- Hours worked per week
- Native country
- Capital gains and losses

You can download the dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult).

## Project Goal
The goal is to develop a model that can predict whether a person’s annual income exceeds $50K based on the demographic features provided. This will be achieved through the following steps:
1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Training and Evaluation
4. Model Tuning and Optimization
5. Insights and Interpretations

## Steps and Techniques
### 1. Data Preprocessing
- Handling missing values (replacing with mode or removing unknowns)
- Encoding categorical variables using techniques like Label Encoding or One-Hot Encoding
- Standardizing/Normalizing continuous variables if necessary
- Splitting the data into training and test sets (e.g., 80% train, 20% test)

### 2. Exploratory Data Analysis (EDA)
- Visualizing the distribution of features such as age, hours-per-week, education level, and more
- Identifying correlations between features
- Analyzing class imbalance (income >50K vs. <=50K)

### 3. Model Training
We will experiment with various models including:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Gradient Boosting (XGBoost, LightGBM)

### 4. Model Evaluation
Evaluation will be based on metrics such as:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Curve

### 5. Model Tuning
We will fine-tune the models using techniques like Grid Search or Random Search with Cross-Validation to improve performance.

## Results
After training, we will compare models to determine the best-performing algorithm. The results will be interpreted to help understand which demographic features have the greatest impact on predicting high income.

## Conclusion and Insights
The project will provide insights into income prediction based on demographic factors, helping businesses or organizations to better understand income-related patterns.


