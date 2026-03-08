# AI Credit Risk Analysis

## Project Overview
This project applies machine learning techniques to predict **credit risk** using borrower information. The objective is to classify whether a loan applicant represents a **good credit risk** or a **bad credit risk** based on demographic and financial attributes.

Credit risk modeling is widely used by financial institutions to reduce loan defaults and support data-driven lending decisions.

---

## Dataset
The project uses the **German Credit Dataset**, which contains information about loan applicants and their financial profiles.

Example features in the dataset include:

- Age
- Job
- Credit amount
- Duration of loan
- Housing status
- Saving accounts
- Checking account status
- Purpose of the loan

**Target Variable**

Risk  
- Good → low credit risk  
- Bad → high credit risk

---

## Project Workflow

### 1. Data Preprocessing
- Loaded dataset using **pandas**
- Removed unnecessary columns (e.g., `Unnamed: 0`)
- Converted categorical variables using **one-hot encoding**
- Prepared features and target variables

### 2. Train-Test Split
The dataset was divided into training and testing sets:

- **80% Training Data**
- **20% Testing Data**

---

## Machine Learning Models

Two classification models were trained and compared:

| Model | Description |
|------|-------------|
| Logistic Regression | Linear model commonly used for classification problems |
| Random Forest | Ensemble tree-based model that improves prediction stability |

---

## Model Evaluation

The models were evaluated using:

- **Accuracy Score**
- **Confusion Matrix**
- **Model Comparison Visualization**

---

## Model Performance

| Model | Accuracy |
|------|----------|
| Logistic Regression | 0.74 |
| Random Forest | 0.73 |

Logistic Regression slightly outperformed Random Forest on this dataset.

---

## Visualization

A bar chart was created to compare model performance.

This visualization helps quickly compare the accuracy of both models.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Installation

Clone the repository:

Navigate to the project folder: https://github.com/BhaveshS0524/credit_risk_analysis.git


---

## Future Improvements

Possible improvements for this project include:

- Hyperparameter tuning
- Cross-validation
- ROC-AUC analysis
- Feature importance analysis
- Model explainability techniques

---

## Author

Bhavesh S
