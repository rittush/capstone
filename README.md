#  House Price Analysis Using Data Science

## Project Overview

The **House Price Analysis Project** aims to analyze property data to identify key factors that influence house prices. Using **data cleaning, exploratory data analysis (EDA), statistical methods, and machine learning techniques**, the project uncovers relationships between property characteristics and pricing.

The goal of this project is to generate **actionable insights and predictive models** that can help real estate stakeholders understand pricing patterns and make informed decisions.

This project follows a structured data analytics workflow including:

* Data collection and preparation
* Exploratory data analysis
* Advanced statistical analysis
* Machine learning modeling
* Insights and business recommendations

---

#  Project Structure

```
project/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   ├── 1_data_cleaning.ipynb
│   ├── 2_eda.ipynb
│   └── 3_analysis.ipynb
│
├── reports/
│   ├── executive_summary.pdf
│   └── technical_report.pdf
│
├── presentations/
│   └── business_presentation.pptx
│
└── README.md
```

### Folder Description

**data/**
Contains the dataset used for analysis.

* `raw_data.csv` → Original dataset
* `cleaned_data.csv` → Processed dataset after cleaning

**notebooks/**
Jupyter notebooks containing step-by-step analysis.

* `1_data_cleaning.ipynb` → Data preprocessing
* `2_eda.ipynb` → Exploratory data analysis
* `3_analysis.ipynb` → Statistical analysis and machine learning

**reports/**
Final project reports.

* `executive_summary.pdf` → High-level findings
* `technical_report.pdf` → Detailed analysis

**presentations/**
Presentation slides summarizing project insights.

---

# Dataset Description

The dataset contains **property details used to analyze house prices**.

### Dataset Features

| Feature       | Description                               |
| ------------- | ----------------------------------------- |
| Property_ID   | Unique identifier for each property       |
| Area          | Total area of the property (square feet)  |
| Bedrooms      | Number of bedrooms                        |
| Bathrooms     | Number of bathrooms                       |
| Age           | Age of the property (years)               |
| Location      | Geographic location of the property       |
| Property_Type | Type of property (Apartment, Villa, etc.) |
| Price         | Selling price of the property             |

### Dataset Size

* Records: **500+ rows**
* Features: **8 variables**

---

# Project Objectives

The main objectives of this project include:

1. Understand factors that influence house prices
2. Explore relationships between property features
3. Identify patterns in real estate pricing
4. Build predictive models for price estimation
5. Generate actionable insights and recommendations

---

# Phase 1: Data Collection & Preparation

Data preparation ensures that the dataset is clean and suitable for analysis.

### Steps Performed

1. Loaded dataset using **Pandas**
2. Inspected dataset structure
3. Checked for missing values
4. Removed duplicate records
5. Converted categorical variables
6. Encoded categorical variables
7. Exported cleaned dataset

### Libraries Used

* Pandas
* NumPy
* Scikit-learn

---

#  Phase 2: Exploratory Data Analysis (EDA)

Exploratory analysis helps understand patterns and relationships within the dataset.

### Key Visualizations Created

1. **Price Distribution Histogram**
2. **Area vs Price Scatter Plot**
3. **Bedrooms vs Price Box Plot**
4. **Property Type vs Price Bar Chart**
5. **Location vs Price Analysis**
6. **Correlation Heatmap**

These visualizations provide insights into how different variables influence property prices.

---

#  Key EDA Insights

Some important patterns identified include:

* Larger houses generally have **higher prices**
* Properties with more bedrooms tend to cost more
* **Location strongly influences property value**
* Property type affects pricing trends
* Older properties may have slightly lower prices

---

#  Phase 3: Advanced Analysis

Three analytical techniques were applied to gain deeper insights.

## Linear Regression

A statistical method used to model the relationship between property features and house price.

Purpose:

* Understand how variables influence price
* Build a predictive model

Evaluation Metrics:

* R² Score
* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)

---

##  Random Forest Regression

A machine learning algorithm that improves prediction accuracy and identifies feature importance.

Advantages:

* Handles complex relationships
* Reduces overfitting
* Provides feature importance insights

---

## Hypothesis Testing

Statistical tests were used to validate relationships between variables.

Example Hypothesis:

H₀: Property area does not affect price
H₁: Property area significantly affects price

Pearson correlation was used to test this hypothesis.

---

# 📊 Model Performance

Model performance was evaluated using regression metrics.

Example results:

```
Model Accuracy: ~90%
R² Score: 0.90
RMSE: 12000
MAE: 10000
```

Interpretation:

* The model explains **about 90% of price variation**
* Prediction errors are relatively small compared to property values

---

# Feature Importance

Random Forest analysis identified the most influential features:

1. Area
2. Location
3. Bedrooms
4. Property Type
5. Age

These factors contribute most significantly to price prediction.

---

# Key Findings

Important insights discovered during the analysis:

* **Area is the strongest predictor of house price**
* Location plays a major role in property value
* Larger homes with more bedrooms are more expensive
* Property type significantly impacts pricing
* Machine learning models can accurately predict house prices

---

# Business Insights & Recommendations

Based on the analysis:

### For Real Estate Developers

Focus on larger properties and desirable locations to maximize property value.

### For Buyers

Consider property age and location when evaluating market price.

### For Real Estate Platforms

Implement machine learning models to improve automated price estimation systems.

---

# Technologies Used

The following tools and libraries were used:

Programming Language:

* Python

Libraries:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Tools:

* Jupyter Notebook
* GitHub

---

# Future Improvements

Possible extensions of this project include:

* Using advanced machine learning models (XGBoost, Gradient Boosting)
* Adding more property features (garage, amenities, parking)
* Incorporating geospatial analysis
* Building a web-based house price prediction tool
* Deploying the model using Flask or Streamlit

---

#  Project Workflow

The project followed a structured data analytics lifecycle:

```
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Statistical Analysis
      ↓
Machine Learning Modeling
      ↓
Insights & Recommendations
```

---

#  Author

House Price Analysis Project
Data Analytics and Machine Learning Project

