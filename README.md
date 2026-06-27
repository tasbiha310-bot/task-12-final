# task-12-final# CoreTech Innovation
## Client Analytics & AI Insights System


## Problem Statement

CoreTech Innovation manages client projects, services, budgets,
and feedback. The purpose of this project is to analyze client data,
discover business patterns, predict project outcomes, and understand
customer satisfaction using Machine Learning and NLP.


# Objectives

- Clean and prepare client data
- Analyze business performance
- Visualize important patterns
- Predict project budgets
- Predict project status
- Analyze customer feedback sentiment
- Generate business recommendations


# Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Scikit-Learn

SQLite

Google Colab

Streamlit


# Dataset

The project uses:

1. Client Dataset

Contains:

- Client information
- Service details
- Project budget
- Duration
- Location
- Lead source
- Status
- Rating


2. Feedback Dataset

Contains:

- Client name
- Service
- Feedback text
- Rating
- Sentiment


# Data Cleaning Steps

Performed:

- Checked missing values
- Removed duplicate rows
- Standardized column names
- Converted data types
- Cleaned feedback text
- Removed unnecessary symbols


Clean dataset:

coretech_clients_cleaned.csv


# Exploratory Data Analysis

Analyzed:

- Highest demand service
- Client distribution by city
- Best lead source
- Average project budget
- Highest budget service
- Project status distribution
- Average rating


# Data Visualization

Created:

## Bar Chart

Shows clients according to services.


## Pie Chart

Shows lead source distribution.


## Line Chart

Shows project budget trends.


## Histogram

Shows rating distribution.


## Scatter Plot

Shows relationship between project duration and budget.



# Machine Learning Models


## 1. Project Budget Prediction

Model:

Linear Regression


Features:

- Service
- Project Duration
- Client City
- Lead Source
- Rating


Evaluation Metrics:

- MAE
- MSE
- RMSE
- R2 Score



## 2. Client Status Prediction

Model:

Random Forest Classifier


Target:

Project Status


Classes:

- Pending
- In Progress
- Completed
- Cancelled


Evaluation:

- Accuracy Score
- Confusion Matrix
- Classification Report



# NLP Sentiment Analysis


Model:

Naive Bayes Classifier


Technique:

CountVectorizer


Tasks:

- Clean feedback text
- Convert text into numerical features
- Classify feedback sentiment


# Model Evaluation

Regression:

MAE measures average prediction error.

RMSE shows prediction error in original units.

R2 Score shows model performance.


Classification:

Accuracy measures correct predictions.

Confusion matrix shows predicted vs actual classes.


NLP:

Classification report shows precision,
recall and F1-score.


# Business Insights

1. Some services have higher client demand than others.

2. Longer projects generally have larger budgets.

3. Positive feedback shows good customer satisfaction.

4. Referral and online sources bring valuable clients.

5. Completed projects represent effective delivery.


# Recommendations for CoreTech Innovation

1. Focus marketing on high-demand services.

2. Promote premium services with higher budgets.

3. Improve customer support using feedback analysis.

4. Use prediction models for better project planning.

5. Expand services in cities with lower client presence.


# How to Run Project


Install libraries:

pip install pandas numpy matplotlib scikit-learn streamlit


Run notebooks using:

Google Colab / Jupyter Notebook


For Streamlit Dashboard:

streamlit run app.py


# Demo Video

Demo Video Link:

(Paste your Google Drive or YouTube link here)


# Conclusion

This project combines data analysis, visualization,
machine learning, and NLP to help CoreTech Innovation
make data-driven business decisions.
