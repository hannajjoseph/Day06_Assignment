# Day6_DataScience_Bootcamp

# Customer Churn Prediction

## Participant Name

Hannah J Joseph

## MUID

hannajjoseph@mulearn

---

# Business Objective

The objective of this project is to predict whether a customer is likely to churn. Early prediction enables businesses to improve customer retention through targeted interventions.

---

# Dataset Overview

**Source:** Customer Churn Dataset

The dataset contains customer demographic and service information along with a churn label.

---

# Features

### Input Features

- CustomerID
- Age
- Gender
- Tenure
- Usage Frequency
- Support Calls
- Payment Delay
- Subscription Type
- Contract Length
- Total Spend
- Last Interaction

### Target

- Churn

---

# Preprocessing Pipeline

- Checked missing values
- Filled missing values
- Label Encoding
- Feature Scaling using StandardScaler
- Train-Test Split (80:20)

---

# Models Implemented

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

# Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|------|---------:|----------:|-------:|---------:|
| Logistic Regression | 0.978087 | 0.981594 | 0.979750 | 0.980671 |
| Decision Tree | **0.999705** | **0.999740** | **0.999740** | **0.999740** |
| Random Forest | 0.999614 | 0.999520 | 0.999800 | 0.999660 |

---

![Missing Values](images/missing_values.png)
# Churn Distribution

![Churn Distribution](images/churn_distribution.png)
# Logistic Regression

![Logistic Regression](images/logistic_cm.png)
# Decision Tree

![Decision Tree](images/decision_tree_cm.png)
# Random Forest

![Random Forest](images/random_forest_cm.png)


# Best Model

**Decision Tree Classifier** achieved the highest accuracy (**99.97%**) and was selected as the best-performing model for this dataset.

---

# Key Observations

- Logistic Regression achieved strong baseline performance.
- Decision Tree produced the highest overall accuracy.
- Random Forest also performed exceptionally with very high precision and recall.
- All three models achieved excellent classification performance.

---

# Business Recommendations

- Identify customers who are likely to churn.
- Offer personalized retention campaigns.
- Improve customer support for high-risk customers.
- Monitor customer engagement regularly.
- Reduce payment delays through proactive reminders.

---

# Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature Engineering
- XGBoost / LightGBM
- Model Deployment using Flask or Streamlit

---

# Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn

---

# Project Structure

```
Day6_DataScience_Bootcamp/
│
├── data/
│   └── customer_churn_dataset-training-master.csv
│
├── images/
│
├── customer_churn_prediction.ipynb
├── requirements.txt
└── README.md
```

---

# Conclusion

This project successfully built multiple machine learning models for customer churn prediction. Among the three models, the **Decision Tree Classifier** achieved the best overall performance with an accuracy of **99.97%**, making it the most suitable model for this dataset.
# Missing Values

