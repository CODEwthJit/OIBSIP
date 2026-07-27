# Sales Prediction Using Python

## Oasis Infobyte Data Science Internship (OIBSIP)

### Task 5

---

## Project Overview

Sales forecasting is a crucial task for businesses aiming to make informed marketing and financial decisions. This project develops a machine learning model to predict product sales based on advertising expenditure across different media channels.

Using historical advertising data for **TV**, **Radio**, and **Newspaper**, the project explores the relationships between advertising investments and sales, applies regression algorithms, and evaluates their predictive performance.

---

## Objective

The objective of this project is to:

- Analyze advertising expenditure data.
- Explore relationships between advertising channels and sales.
- Build machine learning regression models.
- Compare model performance using standard evaluation metrics.
- Predict product sales accurately based on advertising budgets.

---

## Dataset

The dataset contains advertising budgets spent on three different media platforms:

- TV
- Radio
- Newspaper

Target Variable:

- Sales

---

## Project Structure

```text
DataScience-Task5-SalesPrediction/
│
├── dataset/
│   └── Advertising.csv
│
├── Sales_Prediction.ipynb
├── requirements.txt
└── README.md
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Random Forest Regressor

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset Inspection
- Missing Value Analysis
- Descriptive Statistics
- Pair Plot
- Sales vs TV Visualization
- Sales vs Radio Visualization
- Sales vs Newspaper Visualization
- Correlation Heatmap

---

## Model Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Visualizations

This project includes:

- Pair Plot
- Scatter Plots
- Correlation Heatmap
- Residual Plot
- Feature Importance Chart
- Actual vs Predicted Sales Plot
- Model Comparison Table

---

## Results

- TV advertising demonstrated the strongest relationship with product sales.
- Radio advertising also contributed significantly to sales prediction.
- Newspaper advertising showed comparatively lower influence.
- Both regression models achieved good predictive performance.
- The best-performing model was selected based on the highest R² Score and lowest prediction error.

---

## Future Enhancements

Possible improvements include:

- Hyperparameter tuning for better model performance.
- Testing additional regression algorithms such as XGBoost and Gradient Boosting.
- Feature engineering for improved predictions.
- Building a web application for real-time sales prediction.
- Deploying the trained model using Flask or Streamlit.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/OIBSIP.git
```

Navigate to the project directory:

```bash
cd DataScience-Task5-SalesPrediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Sales_Prediction.ipynb
```

---

## Conclusion

This project demonstrates how machine learning can be applied to predict product sales using advertising expenditure. Through exploratory data analysis, visualization, regression modeling, and performance evaluation, the project highlights the importance of data-driven decision-making in marketing and business strategy.

---

## Author

**Biswajit Senapati**

B.Tech Computer Science & Engineering

ITER, Siksha 'O' Anusandhan University

---

## Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Science Internship (OIBSIP)**.
