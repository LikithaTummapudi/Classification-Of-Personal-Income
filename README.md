# Classification-Of-Personal-Income
## 📌 Objective

To classify personal income levels using Machine Learning classification techniques, specifically Logistic Regression and K-Nearest Neighbors (KNN), and to evaluate model performance after preprocessing and feature selection.

### 📊 Exploratory Data Analysis (EDA)
## 1. Getting to Know the Data

Loaded and inspected the dataset

Examined data shape, data types, and basic statistics

Identified categorical and numerical features

Understood the target variable distribution (income class)

### 2. Data Preprocessing

Handled missing values using appropriate strategies
(removal / imputation depending on feature importance)

Encoded categorical variables

Scaled numerical features where required

Split data into training and testing sets

### 3. Cross Tables and Data Visualization

Created cross-tabulations to analyze relationships between:

Education vs Income

Occupation vs Income

Gender vs Income

Visualized patterns using:

Bar plots

Count plots

Histograms

Observed key trends influencing income classification
## Dataset Used

The dataset used in this project is available at the following link:

https://drive.google.com/file/d/1iLmlanshe5wba7TNlTRuyY3r82eYhwAS/view

## 🤖 Machine Learning Models
### 1. Logistic Regression

Implemented Logistic Regression for binary classification

Trained the model on preprocessed data

Evaluated performance using:

Accuracy

Confusion matrix

Classification report

### 2. Logistic Regression – Removing Insignificant Variables

Analyzed feature significance using:

Coefficients

p-values / statistical relevance

Removed variables with low predictive power

Retrained the model with significant features only

Compared performance with the initial model

Observed improvement in interpretability and/or accuracy

### 3. K-Nearest Neighbors (KNN)

Applied KNN classification

Tuned the value of K

Evaluated model performance

Compared results with Logistic Regression

## 📈 Results & Comparison

Compared Logistic Regression and KNN based on:

Accuracy

Precision

Recall

Discussed strengths and limitations of each model

## ✅ Conclusion

Logistic Regression provided clear interpretability

Feature selection improved model efficiency

KNN performance depended strongly on feature scaling and K value

Final model selection based on balanced performance metrics
