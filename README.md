# 🏥 Health Insurance Claim Analysis: Demographic and Health Factors (EDA)

## 📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of a Health Insurance Claims dataset to identify the demographic and health-related factors that significantly influence medical insurance claim amounts.

The project focuses on understanding patterns in healthcare expenses through data preprocessing, visualization, and feature engineering.

---

## 🎯 Objectives

- Perform detailed data preprocessing and cleaning.
- Explore demographic and health-related variables.
- Analyze factors affecting insurance claim amounts.
- Discover hidden relationships using statistical analysis and visualization.
- Engineer meaningful features for predictive modeling.
- Prepare the dataset for Machine Learning applications.

---

## 📂 Dataset Features

| Feature | Description |
|---------|-------------|
| `age` | Age of the insured individual |
| `gender` | Gender of the individual |
| `bmi` | Body Mass Index |
| `bloodpressure` | Blood Pressure Level |
| `diabetic` | Diabetes Status |
| `children` | Number of Dependent Children |
| `smoker` | Smoking Status |
| `region` | Residential Region |
| `claim` | Insurance Claim Amount (Target Variable) |

---

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

- Missing Value Analysis
- Duplicate Record Detection
- Data Type Validation
- Statistical Summary
- Outlier Detection
- Feature Encoding
- Train-Test Split

---

## 📊 Exploratory Data Analysis (EDA)

### Univariate Analysis

- Distribution of Age
- Distribution of BMI
- Distribution of Blood Pressure
- Distribution of Claim Amount
- Category Distribution of Gender, Smoker, Region, etc.

### Bivariate Analysis

Relationship between independent variables and claim amount:

- Age vs Claim
- BMI vs Claim
- Blood Pressure vs Claim
- Gender vs Claim
- Smoker vs Claim
- Diabetic vs Claim
- Region vs Claim

### Multivariate Analysis

- Smoker × BMI × Claim
- Smoker × Diabetic × Claim
- Blood Pressure × Diabetic × Claim
- Age × Smoker × Claim

---

## 🛠️ Feature Engineering

The following new features were engineered:

| Feature | Description |
|----------|-------------|
| `bmi_category` | Categorized BMI into health risk groups |
| `high_bp` | Indicates high blood pressure |
| `health_risk_score` | Combined health risk indicator |
| `bmi_smoker` | Interaction between BMI and smoking status |
| `age_smoker` | Interaction between age and smoking status |
| `smoker_diabetic` | Combined smoking and diabetes risk feature |

---

## 📈 Key Insights

- Smoking is one of the strongest predictors of insurance claims.
- Higher BMI is associated with increased healthcare costs.
- Elevated blood pressure contributes to higher claim amounts.
- Combined risk factors significantly increase insurance expenses.
- Feature engineering enhanced the dataset for predictive modeling.

---

## 📚 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter notebook
```

---

## 🗂️ Project Structure

```bash
Health-Insurance-Claim-EDA/
│
├── data/
│   └── insurance.csv
│
├── notebooks/
│   └── Insurance_Claim_Analysis_Demographic_and_Health(EDA).ipynb
│
├── images/
│   └── visualizations/
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 Future Work

- Build Machine Learning models for claim prediction.
- Compare multiple regression algorithms.
- Hyperparameter tuning.
- Deploy the model using Streamlit.

---

## 📷 Visualizations

This project includes:

- Histograms
- Boxplots
- Scatterplots
- Countplots
- Correlation Heatmaps
- Pairplots
- Bar Charts

---

## 🏆 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

---

## ⭐ Show Your Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**Muhammad Zohaib Khan**

