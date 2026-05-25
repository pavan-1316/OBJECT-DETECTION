# Insurance Cost Prediction using Machine Learning

## Project Overview
This project predicts medical insurance expenses using Machine Learning techniques. The model analyzes factors such as age, BMI, smoking habits, number of children, gender, and region to estimate insurance costs.

The project includes data preprocessing, feature engineering, correlation analysis, visualization, and regression modeling using Python.

---

## Features
- Data Cleaning and Preprocessing
- Feature Engineering
- Pearson Correlation Analysis
- Exploratory Data Analysis (EDA)
- Machine Learning Model Training
- Insurance Expense Prediction
- Data Visualization

---

## Dataset Features

| Feature | Description |
|---|---|
| age | Age of the individual |
| is_female | Gender encoded feature |
| bmi | Body Mass Index |
| children | Number of children |
| is_smoker | Smoking status |
| region_northwest | Region encoding |
| region_southeast | Region encoding |
| region_southwest | Region encoding |
| bmi_category_normal | BMI category |
| bmi_category_overweight | BMI category |
| bmi_category_obese | BMI category |
| expenses | Medical insurance charges |

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## Pearson Correlation Analysis

Pearson correlation was used to measure the relationship between input features and insurance expenses.

```python
from scipy.stats import pearsonr
```

Correlation Formula:

\[
r = \frac{\sum (x_i-\bar{x})(y_i-\bar{y})}
{\sqrt{\sum (x_i-\bar{x})^2 \sum (y_i-\bar{y})^2}}
\]

---

## Machine Learning Workflow
1. Import Dataset
2. Data Cleaning
3. Feature Encoding
4. Correlation Analysis
5. Train-Test Split
6. Model Training
7. Prediction and Evaluation

---

## Model Used
- Linear Regression

Additional models can also be implemented:
- Random Forest Regressor
- XGBoost Regressor
- Decision Tree Regressor

---

## Project Structure

```text
insurance-cost-prediction/
│
├── insurance_cost_prediction.ipynb
├── dataset.csv
├── README.md
├── requirements.txt
└── images/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/insurance-cost-prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Results
- Smoking status showed the highest positive correlation with insurance expenses.
- Age and BMI also significantly affected medical charges.
- The model successfully predicts insurance costs based on user input features.

---

## Future Improvements
- Deploy using Streamlit
- Add advanced regression models
- Improve model accuracy
- Create a web-based prediction system

---

## Author

Pavan K P  
Machine Learning Engineer Aspirant

- GitHub: https://github.com/pavan-1316
- LinkedIn: https://www.linkedin.com/in/contactpavankp

---
