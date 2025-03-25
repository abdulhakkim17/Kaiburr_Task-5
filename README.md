# Kaiburr_Task-5
Data Science example

Consumer Complaint Text Classification

#Overview
This project performs text classification on the Consumer Complaint Dataset, categorizing complaints into four categories:

0 → Credit reporting, repair, or other

1 → Debt collection

2 → Consumer Loan

3 → Mortgage

The pipeline involves Exploratory Data Analysis (EDA), text pre-processing, model selection, evaluation, and performance comparison.

#Project Workflow:

1. Data Collection & Preprocessing
Loaded the dataset from Consumer Complaint Database.

Cleaned the dataset by handling missing values, duplicates, and irrelevant columns.

Pre-processed text (lowercasing, tokenization, stopword removal, lemmatization, etc.).

2. Exploratory Data Analysis (EDA)
Analyzed complaint distribution across categories.

Visualized word frequency and n-grams using matplotlib and seaborn.

Created word clouds for better textual representation.

3. Feature Engineering
Converted text into numerical representations using TF-IDF and CountVectorizer.

Experimented with different feature extraction techniques for better performance.

4. Model Selection
Tested multiple classification models, including:

Logistic Regression

Support Vector Machine (SVM)

Random Forest

Naïve Bayes

6. Prediction
Provided predictions on new complaint texts.

