# 📉 Customer Churn Analysis

This project aims to analyze and predict customer churn using machine learning techniques. Churn analysis helps businesses understand why customers leave and identify patterns that can prevent future loss.

---

## 📊 Project Overview

- **Objective**: Predict whether a customer will churn based on demographic and service usage data.
- **Dataset**: A telecom-style customer dataset with features such as contract type, tenure, monthly charges, etc.
- **Techniques Used**:
  - Data preprocessing & cleaning
  - Exploratory Data Analysis (EDA)
  - Feature engineering
  - Deep learning modeling using TensorFlow (Sequential model with Dense layers)
  - Evaluation with classification report (precision, recall, F1-score)


---

## 📁 Files

- `Churn_Analysis.ipynb`: Jupyter notebook with complete code and visualizations for the analysis and prediction.
- `README.md`: This documentation file.

---

## ⚙️ How to Run

1. Clone the repository or download the notebook.
2. Install dependencies (e.g., pandas, matplotlib, seaborn, scikit-learn):
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```
   jupyter notebook Churn_Analysis.ipynb
   ```
5. Run the cells to reproduce the full analysis and prediction pipeline.

## 📂 Dataset Description

The dataset used in this project is `Customer-Churn-Records.csv`, which contains detailed information about 10,000 customers. The goal is to predict whether a customer will churn (leave the company) based on various features.

### 🔑 Target Variable
- **`Exited`**: Indicates whether the customer has churned.  
  - `1`: Customer left (churned)  
  - `0`: Customer stayed

### 📊 Feature Overview

| Column Name           | Description |
|-----------------------|-------------|
| `RowNumber`           | Row index (not important for modeling) |
| `CustomerId`          | Unique customer identifier |
| `Surname`             | Customer's last name |
| `CreditScore`         | Credit score of the customer |
| `Geography`           | Country (France, Germany, Spain) |
| `Gender`              | Gender of the customer |
| `Age`                 | Customer’s age |
| `Tenure`              | Number of years as a customer |
| `Balance`             | Account balance |
| `NumOfProducts`       | Number of banking products held |
| `HasCrCard`           | Has credit card? (1 = Yes, 0 = No) |
| `IsActiveMember`      | Is the customer active? (1 = Yes, 0 = No) |
| `EstimatedSalary`     | Estimated yearly income |
| `Complain`            | Has the customer made a complaint? (1 = Yes, 0 = No) |
| `Satisfaction Score`  | Satisfaction rating (1 to 5) |
| `Card Type`           | Type of credit card (DIAMOND, PLATINUM, GOLD, SILVER) |
| `Point Earned`        | Loyalty points collected by the customer |

This dataset provides a rich mix of numerical and categorical features that are useful for building predictive models.

