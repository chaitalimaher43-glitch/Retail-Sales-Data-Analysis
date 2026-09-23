# Retail Sales Data Analysis with AI

## Project Overview

This project analyzes retail sales data using Python and Jupyter Notebook. It includes data cleaning, exploratory data analysis, business KPI analysis, visualization, and machine-learning-based sales forecasting.

The project uses a Superstore-style retail sales dataset. A Random Forest Regressor is used to forecast monthly sales based on time-related and historical sales features.

## Project Objectives

- Load and inspect the retail sales dataset.
- Clean and prepare the data for analysis.
- Create time-based features such as Year, Month, Quarter, and Day of Week.
- Calculate important retail business KPIs.
- Analyze sales trends and seasonality.
- Compare sales by category, sub-category, product, region, state, and customer segment.
- Build a Random Forest model for monthly sales forecasting.
- Evaluate the model using MAE, RMSE, and R².
- Generate a six-month recursive sales forecast.
- Generate automated business insights.

## Dataset

**Dataset:** Superstore-style retail sales dataset

The project loads the dataset from a CSV file. The notebook requires the `Order Date` and `Sales` columns and uses additional fields such as `Ship Date`, `Order ID`, `Product ID`, `Product Name`, `Category`, `Sub-Category`, `Region`, `State`, and `Segment` when available.

**Dataset link:** https://drive.google.com/file/d/1Y8Lcr7pKl3BfBi3gkFK84y_W1sOUHWvS/view?usp=sharing.



## Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

## Machine Learning

The project uses a `RandomForestRegressor` for monthly sales forecasting.

The model uses:

- Year
- Month
- Quarter
- Time Index
- 1-month sales lag
- 2-month sales lag
- 3-month sales lag
- 3-month rolling average
- 6-month rolling average

The model is evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² (R-squared)

A chronological train/test split is used to maintain the time order of the sales data.

## Project Workflow

1. Load the CSV dataset.
2. Inspect columns, data types, missing values, and duplicates.
3. Clean date and sales fields.
4. Remove invalid and negative sales records.
5. Create time-based features.
6. Calculate business KPIs.
7. Perform exploratory data analysis.
8. Analyze category, product, regional, state, and segment performance.
9. Prepare monthly sales data for machine learning.
10. Train and evaluate the Random Forest model.
11. Generate a six-month recursive forecast.
12. Generate automated business insights.

## Setup and Run Instructions

### 1. Clone or download the project

Download or clone this repository to your computer.

### 2. Install Python

Install Python 3.x on your system.

### 3. Install required libraries

Open the project folder in Command Prompt or VS Code terminal and run:

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

Run:

```bash
jupyter notebook
```

Then open:

```text
Chaitali_RetailSalesDataAnalysis.ipynb
```

### 5. Add the dataset

Place the required CSV dataset in the project folder or update the CSV path in the notebook according to your dataset location.

### 6. Run the notebook

Run the notebook cells from top to bottom to perform the complete analysis and generate the charts, model results, forecast, and automated insights.

## Project Files


RetailSalesDataAnalysis/
│
├── Chaitali_RetailSalesDataAnalysis.ipynb
├── requirements.txt
├── Chaitali_RetailSalesDataAnalysis_ProjectReport.docx
└── README.md


## Key Outputs

The project produces:

- Retail sales KPIs
- Monthly sales trend
- Year-over-year monthly comparison
- Seasonality analysis
- Category and sub-category analysis
- Top and bottom product analysis
- Regional and state analysis
- Customer segment analysis
- Actual vs. predicted sales comparison
- Feature importance
- Model evaluation metrics
- Six-month future sales forecast
- Automated business insights


## Author

**Chaitali Maher**

**Project:** Retail Sales Data Analysis with AI  
**Internship:** AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026
