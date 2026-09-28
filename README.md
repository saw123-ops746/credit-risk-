# Credit Risk Prediction Using Machine Learning

A Machine Learning project that predicts the **credit risk of a loan applicant** based on financial and personal information.

The project includes data preprocessing, exploratory data analysis, feature engineering, machine learning model training, model evaluation, and a saved trained model for future predictions.

## 📌 Project Overview

Credit risk assessment is an important task for banks and financial institutions.

The objective of this project is to use historical loan applicant data to build a machine learning model that can identify whether an applicant represents a **higher or lower credit risk**.

### 🎯 Objective

* Analyze historical credit risk data
* Perform data cleaning and preprocessing
* Explore relationships between features and credit risk
* Train a machine learning classification model
* Evaluate model performance using appropriate metrics
* Save the trained model for future predictions

---

## 📂 Project Structure

```text
credit-risk-/
│
├── main.ipynb
│   └── Complete data analysis, preprocessing,
│       model training and evaluation
│
├── credit_risk_dataset.csv
│   └── Dataset used for training and analysis
│
├── credit_risk_model.pkl
│   └── Trained machine learning model
│
└── README.md
    └── Project documentation
```

---

## 📊 Dataset

The project uses a credit risk dataset containing information about loan applicants.

Typical features include information related to:

* Person's income
* Age
* Employment information
* Loan amount
* Loan interest rate
* Loan-to-income relationship
* Credit history
* Previous credit information
* Loan status / credit risk

The target variable represents the credit risk classification.

---

## 🔍 Exploratory Data Analysis

The project performs exploratory analysis to understand the dataset and identify important patterns.

The analysis includes:

* Data distribution
* Missing-value analysis
* Outlier detection
* Correlation analysis
* Feature relationships
* Target-variable distribution
* Statistical analysis
* Data visualization

Visualizations are created using Python data-analysis and visualization libraries.

---

## ⚙️ Machine Learning Workflow

The project follows this general workflow:

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
Data Preprocessing
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Saving
   ↓
Future Predictions
```

---

## 🤖 Machine Learning

The problem is treated as a **classification problem** because the model predicts a credit-risk category.

The trained model is saved as:

```text
credit_risk_model.pkl
```

This allows the trained model to be loaded later without training it again.

---

## 📈 Model Evaluation

The model can be evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

These metrics help evaluate how well the model identifies different credit-risk classes.

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

### Development Environment

* Jupyter Notebook
* VS Code
* Git
* GitHub

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/saw123-ops746/credit-risk-.git
```

### 2. Navigate to the project

```bash
cd credit-risk-
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

and run the notebook cells.

---

## 💾 Using the Trained Model

The trained model is stored in:

```text
credit_risk_model.pkl
```

It can be loaded using Python:

```python
import pickle

with open("credit_risk_model.pkl", "rb") as file:
    model = pickle.load(file)
```

The loaded model can then be used to make predictions on new applicant data.

---

## 📌 Key Concepts Demonstrated

This project demonstrates practical knowledge of:

* Data preprocessing
* Exploratory Data Analysis
* Statistical analysis
* Feature engineering
* Classification
* Machine Learning
* Model evaluation
* ROC-AUC
* F1 Score
* Confusion Matrix
* Probability prediction
* Model serialization using Pickle

---

## 🔮 Future Improvements

Possible future improvements include:

* Build a Streamlit web application
* Add real-time credit-risk prediction
* Add probability calibration
* Add SHAP-based model explainability
* Create an interactive dashboard
* Deploy the model online
* Add API support using FastAPI
* Improve model monitoring and validation

---

## 👨‍💻 Author

**Hritik Saw**

B.Sc. Data Science Student
Interested in Machine Learning, Data Science and AI.

### GitHub

https://github.com/saw123-ops746

### Project Repository

https://github.com/saw123-ops746/credit-risk-

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.
