 🚢 Titanic Survival Prediction Dashboard

An interactive machine learning dashboard that predicts passenger survival on the Titanic using demographic and travel-related information. The project combines data exploration, feature engineering, model evaluation, and real-time survival prediction to demonstrate how classification algorithms can uncover patterns from historical data.



 📊 Overview

This project uses the famous Titanic dataset to train and evaluate machine learning models capable of predicting whether a passenger survived the Titanic disaster. The dashboard provides comprehensive visualizations, model comparisons, feature importance analysis, and an interactive survival predictor.

Users can:

* Explore passenger demographics and survival trends
* Visualize survival rates across classes, genders, and age groups
* Compare machine learning model performance
* Analyze confusion matrices and evaluation metrics
* Predict survival probability using custom passenger profiles



✨ Features

📈 Exploratory Data Analysis Dashboard

* Dataset overview and statistics
* Survival distribution analysis
* Passenger class insights
* Age group survival trends
* Missing value analysis
* Feature importance visualization

 📉 Passenger Insights Analysis

* Survival by gender
* Survival by passenger class
* Age-based survival patterns
* Fare distribution analysis
* Embarkation port analysis
* Family size impact on survival

 🤖 Model Performance Comparison

* Logistic Regression Evaluation
* Random Forest Evaluation
* Gradient Boosting Evaluation
* Accuracy Comparison
* Precision, Recall, and F1 Score Analysis
* Best Model Recommendation

 🔍 Confusion Matrix Analysis

Visual representation of model predictions showing:

* True Positives
* True Negatives
* False Positives
* False Negatives
* Classification accuracy
* Prediction reliability

🚢 Live Survival Predictor

Enter passenger information and instantly receive:

* Survival Prediction
* Survival Probability
* Risk Assessment
* Feature Impact Analysis
* Personalized Prediction Insights



 🧠 Machine Learning Pipeline

 Dataset

 Titanic Dataset

* 891 Passenger Records
* 12 Features
* Binary Classification Problem
* Survival Target Variable


 Data Preprocessing

 Data Cleaning

* Missing value handling
* Age imputation
* Embarked value completion
* Feature validation

 Feature Engineering

* Title extraction from passenger names
* Family Size creation
* IsAlone feature generation
* Age binning
* Fare categorization
* Label encoding for categorical variables



 Models

 Logistic Regression

A linear classification algorithm used as a baseline model for predicting passenger survival.

 Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees for improved prediction accuracy.

 Gradient Boosting Classifier

A boosting-based model that sequentially improves predictions by correcting previous errors.



## Evaluation Metrics

| Metric           | Logistic Regression | Random Forest | Gradient Boosting |
| ---------------- | ------------------- | ------------- | ----------------- |
| Accuracy         | 81.6%               | 82.1%         | 81.0%             |
| Precision        | 80%                 | 78%           | 79%               |
| Recall           | 74%                 | 78%           | 73%               |
| Cross Validation | 79.9%               | 81.5%         | 81.3%             |

 🏆 Best Performing Model: Random Forest


 📋 Features Used

| Feature     | Description                       |
| ----------- | --------------------------------- |
| Pclass      | Passenger ticket class            |
| Sex         | Passenger gender                  |
| Age         | Passenger age                     |
| SibSp       | Number of siblings/spouses aboard |
| Parch       | Number of parents/children aboard |
| Fare        | Ticket fare paid                  |
| Embarked    | Port of embarkation               |
| Title       | Extracted social title            |
| Family Size | Total family members aboard       |
| Is Alone    | Whether passenger traveled alone  |



 🎯 Target Variable

 Survival Status

* Survived (1)
* Did Not Survive (0)



 🛠️ Technologies Used

 Machine Learning

* Python
* Scikit-learn
* Pandas
* NumPy

 Frontend

* HTML5
* CSS3
* JavaScript

 Data Visualization

* Chart.js
* Interactive Dashboards



 📸 Dashboard Preview

 Overview Dashboard

* Survival Statistics
* Passenger Distribution
* Feature Importance Analysis
* Key Performance Indicators

 Dataset Explorer

* Searchable Passenger Records
* Filtering Options
* Missing Value Analysis
* Data Inspection Tools

 Exploratory Data Analysis

* Survival Trends
* Demographic Analysis
* Fare and Age Distributions
* Class-Based Comparisons

 Model Evaluation

* Accuracy Comparison
* Performance Metrics
* Confusion Matrices
* Cross Validation Results

 Live Predictor

Users can adjust passenger characteristics and generate survival predictions in real time.


🚀 Getting Started

 Clone the Repository

```bash
git clone https://github.com/sssxrxhhh07/titanic-survival-prediction-dashboard.git

cd titanic-survival-prediction-dashboard
```

 Open the Dashboard

Simply open:

```bash
titanic-ds-app.html
```

in your browser.

No additional setup is required.



 📊 Model Interpretation

 Most Important Features

✅ Sex (28.6%)

✅ Passenger Title (16.2%)

✅ Passenger Class (14.3%)

These features contribute the most to predicting passenger survival.



 Moderate Impact Features

* Family Size
* Fare
* Age

These factors influence survival probability but are less dominant than gender and class.


 Less Influential Features

* Embarked Port
* IsAlone

While useful, these features have relatively lower predictive power.


 🔍 Key Insights

 Women Had Higher Survival Rates

Women survived at approximately 74.2%, compared to only 18.9% for men.

First-Class Advantage

First-class passengers had a survival rate of **63%**, while third-class passengers survived at only **24.2%**.

 Children Were Prioritized

Passengers under the age of 12 experienced significantly higher survival rates due to evacuation policies.

 Social Status Influenced Survival

Passenger titles such as *Mrs.*, *Miss.*, and *Master* carried predictive information about survival outcomes.


 📈 Sample Results

| Metric                       | Value          |
| ---------------------------- | -------------- |
| Dataset Size                 | 891 Passengers |
| Features                     | 12             |
| Target Classes               | 2              |
| Missing Age Values           | 177            |
| Missing Cabin Values         | 687            |
| Random Forest Accuracy       | 82.1%          |
| Logistic Regression Accuracy | 81.6%          |
| Gradient Boosting Accuracy   | 81.0%          |
| Best Model                   | Random Forest  |



 🎯 Learning Objectives

This project demonstrates:

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Feature Engineering
* Classification Algorithms
* Ensemble Learning
* Model Evaluation
* Confusion Matrix Analysis
* Feature Importance Interpretation
* Interactive Machine Learning Dashboards
* Real-Time Prediction Systems


 🔮 Future Improvements

* Add XGBoost Classifier
* Implement Hyperparameter Tuning
* Perform K-Fold Cross Validation
* Add SHAP Explainability Visualizations
* Deploy Using Flask or Streamlit
* Real-Time Dataset Upload Support
* Model Export and API Integration
* Advanced Survival Probability Analysis



⭐ If you found this project useful, consider giving the repository a star and sharing your feedback! 🚢📊🤖
