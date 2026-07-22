# 🚲 Bike Sharing Demand Prediction using Multiple Linear Regression

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Regression-F7931E.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## Project Overview

This project builds a **Multiple Linear Regression** model to predict the daily demand for shared bikes in the American market.

The analysis was completed as part of the **PG Diploma in Machine Learning and AI**. The objective was to help **BoomBikes**, a bike-sharing company, understand the major factors influencing bike rentals so that it can optimize business strategy and improve demand forecasting after the COVID-19 pandemic.

---

## Business Problem

BoomBikes experienced a significant decline in revenue during the COVID-19 pandemic.

The company wanted to answer two important business questions:

- Which variables significantly affect bike rental demand?
- How well can these variables explain daily bike demand?

The resulting model enables management to understand customer demand patterns and make data-driven operational decisions.

---

## Dataset

The dataset contains **731 daily observations** with weather, seasonal, and calendar-related information.

### Target Variable

- **cnt** — Total number of bike rentals

### Predictor Variables

- Season
- Year
- Month
- Holiday
- Weekday
- Working Day
- Weather Situation
- Temperature
- Feeling Temperature
- Humidity
- Wind Speed

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning

- Loaded dataset
- Checked missing values
- Verified data types
- Removed unnecessary variables

---

### 2. Exploratory Data Analysis

Performed:

- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Pair Plot
- Heatmap
- Boxplots
- Distribution Analysis

---

### 3. Feature Engineering

- Converted categorical variables
- Created dummy variables
- Dropped redundant variables
- Applied feature scaling

---

### 4. Model Building

- Train-Test Split
- Multiple Linear Regression
- Recursive Feature Elimination (RFE)
- Variance Inflation Factor (VIF)
- Feature Selection

---

### 5. Model Validation

Validated Linear Regression assumptions using:

- Residual Distribution
- Residual Scatter Plot
- Q-Q Plot
- Multicollinearity (VIF)
- Homoscedasticity

---

### 6. Model Evaluation

Performance evaluated using:

- R² Score
- Adjusted R²
- Residual Analysis

---

## Results

The final regression model achieved an **R² score of approximately 0.81**, indicating that the selected variables explain a substantial proportion of the variation in daily bike rental demand. :contentReference[oaicite:0]{index=0}

### Most Important Features

- 🌡️ Temperature
- 🌦️ Weather Situation
- 🌸 Spring Season
- 🏢 Working Day
- ☀️ Year

---

## Key Business Insights

- Bike demand increases significantly during favorable weather conditions.
- Temperature has a strong positive influence on rentals.
- Spring season experiences comparatively lower demand.
- Working days contribute positively to overall rentals.
- Demand increased from 2018 to 2019, indicating growing adoption of bike-sharing services.

These insights can help BoomBikes improve fleet planning, pricing strategies, and marketing campaigns.

---

## Repository Structure

```
bike-sharing-demand-prediction/
│
├── data/
│   └── day.csv
│
├── notebooks/
│   └── bike_sharing_regression.ipynb
│
├── presentation/
│   ├── Bike_Sharing_Project_Presentation.pptx
│   └── Subjective_Questions.pptx
│
├── images/
│   ├── correlation_heatmap.png
│   ├── pairplot.png
│   ├── model_summary.png
│   ├── residual_distribution.png
│   ├── actual_vs_predicted.png
│   └── results.png
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Visualizations

### Correlation Heatmap

![Heatmap](images/correlation_heatmap.png)

---

### Pair Plot

![Pairplot](images/pairplot.png)

---

### Model Summary

![Model Summary](images/model_summary.png)

---

### Residual Distribution

![Residual Distribution](images/residual_distribution.png)

---

### Actual vs Predicted

![Actual vs Predicted](images/actual_vs_predicted.png)

---

## Conclusion

A Multiple Linear Regression model was successfully developed to predict bike rental demand using environmental and calendar-related variables.

The analysis demonstrates that weather conditions, seasonal effects, and temperature play a significant role in determining daily bike rentals. The model provides valuable insights that can support strategic planning and operational decision-making for bike-sharing businesses.

---

## Author

**Hanaa Parvez Khan**

- MSc Data Science
- Data Analyst | Machine Learning | Data Science
- GitHub: *Add your GitHub profile link*
- LinkedIn: *Add your LinkedIn profile link*

---

## License

This project is licensed under the MIT License.
