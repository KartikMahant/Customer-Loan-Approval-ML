# Customer Loan Approval Prediction

## Overview
This project focuses on predicting whether a customer’s loan application will be approved using Machine Learning techniques. The notebook includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and hyperparameter tuning.

The main goal is to help financial institutions automate the loan approval process while reducing risk and improving decision-making efficiency.

---

## Business Objective
- Minimize loan default risk
- Improve approval decision accuracy
- Automate manual loan screening
- Build a scalable data-driven prediction system

---

## Dataset Information

The dataset contains customer financial and personal information used to determine loan approval status.

### Features Used
Some important features include:
- Applicant Income
- Age
- Credit Score
- Loan Amount
- Employment Information
- Other financial indicators

### Target Variable

| Value | Meaning |
|------|------|
| 1 | Loan Approved |
| 0 | Loan Rejected |

### Dataset Shape
- Rows: **45,000**
- Columns: **14**

---

## Project Workflow

### 1. Data Loading
- Loaded dataset using Pandas
- Inspected structure and missing values

### 2. Data Cleaning
- Handled missing values
- Removed unrealistic age values
- Treated outliers
- Prepared clean dataset for modeling

### 3. Exploratory Data Analysis (EDA)

Performed:
- Univariate Analysis
- Bivariate Analysis
- Distribution visualization
- Correlation analysis

Key insights explored:
- Income distribution
- Credit score impact on loan approval
- Loan amount trends
- Class balance

### 4. Feature Engineering
- Encoded categorical variables
- Prepared features for machine learning algorithms

### 5. Model Building

Implemented multiple machine learning models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 6. Model Evaluation

Used:
- Cross Validation
- Accuracy Score
- Standard Deviation Analysis

### 7. Hyperparameter Tuning
Applied `GridSearchCV` for Random Forest optimization.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models

### Logistic Regression
A baseline linear classification model.

### Decision Tree
A tree-based model used for interpretable predictions.

### Random Forest
An ensemble learning model that achieved the best performance after tuning.

---

## Project Structure

```bash
Customer-Loan-Approval/
│
├── Customer_loan_approval.ipynb
├── loan_data.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-loan-approval.git
cd customer-loan-approval
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
Customer_loan_approval.ipynb
```

---

## Results
- Compared multiple machine learning algorithms
- Random Forest produced the best accuracy after tuning
- Improved prediction consistency using cross-validation

---

## Future Improvements
- Deploy model using Flask or FastAPI
- Build an interactive web application
- Add advanced feature engineering
- Experiment with XGBoost and LightGBM
- Integrate real-time loan prediction API

---

## Screenshots
You can add:
- EDA visualizations
- Confusion matrix
- Feature importance charts
- Model comparison graphs

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to your branch
5. Open a Pull Request

---

## License
This project is open-source and available under the MIT License.

---

## Author
Kartik Mahant
