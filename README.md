❤ Heart Disease Prediction Model 🩺
🌟 Project Overview
This project is a comprehensive analysis of a heart disease dataset, designed to explore key physiological and clinical factors and build a robust machine learning model capable of predicting the presence of heart disease in patients.

We utilized Python libraries like Pandas, Matplotlib, and Scikit-learn to perform Exploratory Data Analysis (EDA), visualize important features, and train classification algorithms.

💾 Dataset & Initial Analysis
The analysis is based on a dataset containing 14 key features for patient diagnosis.

Columns Analyzed:
Feature

Description

age

Patient Age

sex

Patient Gender

cp

Chest Pain Type

thalachh

Maximum Heart Rate Achieved

chol

Cholesterol

output

Target variable (0: No Disease, 1: Disease)

Key Findings from EDA 📈
Data Quality: No missing values were found, and the data was clean and ready for processing.

Age Distribution: The distribution of age was visualized, showing a strong concentration in the mid-50s to early 60s.

Feature Relationships:

A Correlation Matrix revealed which features correlate most strongly with the target variable (output).

Maximum Heart Rate Achieved (thalachh) and Chest Pain Type (cp) showed significant relationships with heart disease presence.

🤖 Machine Learning Modeling
We tested two popular classification algorithms for predicting heart disease and evaluated their performance across multiple metrics.

1. Model Training & Evaluation
The data was split into training and testing sets (80% train, 20% test) and standard scaling was applied to optimize performance, particularly for the Logistic Regression model.

Algorithm

Feature Scaling Used

Logistic Regression

Baseline (Unscaled) and Scaled

Random Forest Classifier

Baseline (Unscaled) and Scaled

2. Best Model Performance 🏆
The Random Forest Classifier provided the best overall performance, demonstrating excellent predictive capability on the test set:

Metric

Result

Interpretation

Accuracy

0.8361

Overall percentage of correct predictions.

Precision

0.7805

Of all predicted positive cases, 78% were truly positive.

Recall

0.9697

Model correctly identified 97% of all actual positive cases (true heart disease patients).

F1-Score

0.8649

Harmonic mean of Precision and Recall.

💻 Setup and Usage
To run this analysis and replicate the model, follow these steps:

Clone the repository:

git clone [Your Repository URL Here]

Install dependencies:
This project requires standard data science libraries.

pip install pandas numpy matplotlib seaborn scikit-learn

Run the analysis:
Execute the code found in the heart_disease - Colab.pdf (or your main notebook file) to load the data, run the EDA, and train the models.

# Example command to run the Python script/notebook
python run_model_analysis.py

🤝 Contribution
Contributions are welcome! If you have suggestions for feature engineering, hyperparameter tuning, or trying new models (like SVM or Gradient Boosting), please open an issue or submit a pull request.

Created with a passion for data science and heart health! 💖
