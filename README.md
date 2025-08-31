# Heart-Disease-Prediction

## Project Overview

Cardiovascular disease (CVD) is one of the leading causes of death worldwide. Early detection and analysis of risk factors can help improve prevention strategies. This project explores health metrics from heart patients, including age, blood pressure, heart rate, and more. The goal is to develop a predictive model capable of accurately identifying individuals with heart disease. Given the grave implications of missing a positive diagnosis, the main emphasis is making sure that the model identifies all potential patients, making recall for the positive class a crucial metric.

---

## Dataset Used

- **Dataset**: [Cleveland Heart Disease Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data)
- **Source**: UCI Machine Learning Repository
- **Features**:
  - **Numerical Variables**: Age, Cholesterol, Blood Pressure, Oldpeak (ST depression)
  - **Categorical Variables**: Chest Pain Type, Fasting Blood Sugar, Resting ECG, Exercise Induced Angina, Thalassemia, etc.
  - **Target Variable**: Presence (1) or Absence (0) of heart disease

---

## Methodology

### 1**Data Preprocessing**

- Handled missing values by replacing `0` values with `NaN` and filling them with median values.
- Converted categorical columns to proper data types.
- Scaled numerical features for better model performance.

### **Exploratory Data Analysis (EDA)**

- Visualized distributions of numerical and categorical features.
- Boxplots to compare numerical variables with the target class.
- Heatmaps to analyze feature correlations.

### **Machine Learning Modeling**

- Implemented Logistic Regression, Random Forest, and Support Vector Machine (SVM).
- Used cross-validation for reliable model performance.
- Evaluated models based on accuracy, precision, recall, and F1-score.

---

## How to Run This Project

### **Installation Steps**

Clone the repository:

```bash
git clone https://github.com/yourusername/CVD-Analysis.git
cd CVD-Analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
CVD
```

Open and run the analysis notebook located in the `notebooks/` folder.

---

## Key Features

- **Patients with high cholesterol and high blood pressure showed a strong correlation with CVD.**
- **Exercise Induced Angina and ST depression were critical indicators of heart disease risk.**
- **Machine Learning models achieved an accuracy of ~75% in predicting heart disease.**

---

## Connect & Contribute

If you find this project useful, consider giving it a star on GitHub!

Contributions are welcome! Feel free to open an issue or submit a pull request.
Contact: deniz.yener@proton.me
