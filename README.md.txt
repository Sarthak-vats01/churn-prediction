# 📉 Customer Churn Prediction Using Machine Learning

This project focuses on identifying the key drivers of customer churn using a classification model. With a combination of exploratory data analysis, visualizations, and machine learning techniques (Random Forest), we determine the most important features that affect whether a customer is likely to churn.

---

## 📁 Project Structure


---

## 🎯 Objectives

- Perform **Exploratory Data Analysis (EDA)** to understand customer behavior
- Train a **Random Forest Classifier** to predict churn
- Visualize **feature importance**
- Analyze **days_since_joining** vs churn with boxplots

---

## 📦 Tools & Libraries Used

- Python 🐍
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (RandomForestClassifier)
- Jupyter Notebook

---

## 🧠 Key Features Analyzed

- `avg_spend` – Average spend per customer
- `total_spend` – Total amount spent
- `days_since_joining` – How long the user has been with the platform
- `transaction_count` – Number of transactions
- `is_churned` – Target variable

---

## 📊 Visualizations

### 1. Feature Importance (from Random Forest)

The chart below shows which features most influence churn:

![Feature Importance](images/feature_importance.png)

- `avg_spend` and `transaction_count` had the strongest impact
- `days_since_joining` showed moderate importance

---

### 2. Boxplot – Days Since Joining vs Churn

A visual representation of churn based on user tenure:

![Boxplot](images/boxplot_days_since_joining.png)

- Customers with both short and long tenure have similar churn patterns.
- Median days_since_joining is slightly lower for churned users, but no sharp trend.

---

## 🏗️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/churn-prediction.git
   cd churn-prediction
