# Invistico Airlines Passenger Satisfaction Prediction

## ✈️ Project Overview

This project is part of the lab work for Google Advanced Data Analytics Specialization courses 5 (Regression Analysis) and 6 (The Nuts and Bolts of Machine Learning), and applies multiple machine learning algorithms to predict passenger satisfaction for Invistico Airlines using real-world customer data. Models developed include Binomial Logistic Regression, Decision Tree, Random Forest, and XGBoost, each evaluated for performance and interpretability. The goal is to enable data-driven improvements in customer experience and operational efficiency for the airline.

## 📋 Table of Contents

* [Business Problem](#-business-problem)
* [Data Description](#-data-description)
* [Methodology](#-methodology)
* [Model Results](#-model-results)
* [Key Insights & Recommendations](#-key-insights--recommendations)
* [Future Work](#-future-work)
* [References](#-references)

## 💼 Business Problem

Invistico Airlines seeks to better understand the drivers of passenger satisfaction and proactively address factors leading to dissatisfaction. Predictive modeling can help prioritize operational and service improvements.

## 📊 Data Description

The dataset includes passenger survey data and flight information, with features such as:

* **Customer Type** (Loyal/Disloyal)
* **Age**
* **Flight Distance**
* **On-time Performance**
* **Inflight Service Ratings** (e.g., seat comfort, food, entertainment)
* **Class**
* **Satisfaction** (Target: Satisfied/Not Satisfied)

*See individual notebooks for complete variable lists and preprocessing details.*


## 🧭 Methodology

* **Data Cleaning & Preparation:**
  Handled missing values, encoded categorical variables, and standardized features as needed.
* **Exploratory Data Analysis:**
  Explored satisfaction distributions and relationships between key features and the target.
* **Model Building:**

  * *Binomial Logistic Regression* for interpretability
  * *Decision Tree* for basic non-linear modeling
  * *Random Forest* for improved performance and feature importance
  * *XGBoost* for state-of-the-art predictive accuracy
* **Model Evaluation:**
  Compared models using accuracy, precision, recall, F1-score, and ROC-AUC where applicable.

## 📈 Model Results

| Model               | Accuracy    | Precision    | Recall    | F1-score    |
| ------------------- | --------    | ---------    | ------    | --------    |
| Logistic Regression | 0.801       | 0.816        | 0.821     | 0.818       |
| Decision Tree       | 0.945       | 0.935        | 0.955     | 0.940       |
| Random Forest       | 0.947       | 0.944        | 0.950     | 0.942       |
| XGBoost             | 0.939       | 0.932        | 0.946     | 0.934       |

The Random Forest model achieved the highest overall performance (accuracy: 94.7%, F1-score: 0.942), making it the preferred choice for predicting passenger satisfaction in this analysis. It balances high precision and recall, indicating strong capability to both correctly identify satisfied passengers and minimize false positives/negatives.


## 📝 Key Insights & Recommendations

* **Customer Experience:**
  Inflight service quality and seat comfort are critical to satisfaction scores.
* **Operational Improvements:**
  On-time performance has a measurable impact on satisfaction—targeted improvements can increase loyalty.
* **Segmented Interventions:**
  Loyal customers and business-class flyers are more likely to be satisfied; focus efforts on disloyal and economy-class segments for higher impact.

## 🚀 Future Work

* **Deployment:**
  Develop a dashboard for real-time satisfaction prediction and monitoring.

## 📚 References

* Scikit-learn, XGBoost, pandas, matplotlib documentation

---

*Prepared by Ashraf Un Noor as part of the coursework for Google Advanced Data Analytics Specialization*
