# Buenos Aires Housing Price Prediction

## Project Overview

This repository documents my work from the **Buenos Aires Housing Price Prediction** module in the **WorldQuant Applied Data Science Lab**. Throughout this module, I applied Python-based machine learning techniques to build regression models capable of predicting apartment prices in Buenos Aires, Argentina.

The notebooks walk through the complete machine learning workflow—from preparing and exploring housing datasets to engineering predictive features, building regression models, and evaluating their performance. As the module progresses, additional property characteristics such as **apartment size**, **geographic location**, and **neighborhood information** are incorporated to improve prediction accuracy.

Rather than serving as a standalone portfolio project, this repository represents an important milestone in my learning journey, where I strengthened my practical skills in data preparation, feature engineering, supervised machine learning, and regression analysis using real-world housing datasets.


## Learning Context

This repository was developed as part of the **WorldQuant Applied Data Science Lab**, a hands-on program designed to build practical machine learning skills using real-world datasets.

The Buenos Aires Housing Price Prediction module introduces learners to the complete supervised machine learning workflow. Through a series of guided notebooks, I learned how to prepare housing data, engineer predictive features, build regression models, evaluate model performance, and interpret machine learning results using industry-standard Python libraries such as **Pandas**, **NumPy**, **Matplotlib**, and **Scikit-learn**.

Each notebook builds upon concepts introduced in the previous one, allowing me to progressively develop practical skills in data preprocessing, regression analysis, feature engineering, and machine learning pipelines while working with real-world housing data.


## Learning Objectives

Through this module, I developed practical experience in building and evaluating regression models using Python and Scikit-learn. The learning objectives included:

- Preparing housing datasets for supervised machine learning.
- Cleaning data and handling missing values through preprocessing techniques.
- Engineering meaningful features to improve predictive performance.
- Building and evaluating **Linear Regression** and **Ridge Regression** models.
- Comparing how apartment size, geographic location, and neighborhood information influence housing prices.
- Constructing reusable machine learning pipelines using **Scikit-learn**.
- Interpreting regression coefficients and analyzing feature importance.
- Generating and evaluating housing price predictions using real-world datasets.


## Dataset Overview

The analysis is based on residential apartment listing data from **Buenos Aires, Argentina**. Throughout the module, the dataset is progressively cleaned and transformed to support the development of increasingly accurate regression models for predicting apartment prices.

The dataset contains information about various property characteristics, including:

- Apartment price
- Covered surface area
- Geographic coordinates (latitude and longitude)
- Neighborhood information
- Additional property attributes used for feature engineering and model development

Working with this dataset provided an opportunity to practice data cleaning, feature selection, preprocessing, and feature engineering while preparing data for supervised machine learning. As new features were introduced across the notebooks, I explored how each contributed to improving the predictive performance of the regression models.


## Notebook Breakdown

The repository is organized into a series of Jupyter Notebooks that progressively build practical machine learning skills through the development of regression models for predicting apartment prices.

### 01 – Predicting Price with Size

Introduces supervised machine learning by building a simple **Linear Regression** model using apartment size as the primary predictor. This notebook covers data cleaning, exploratory visualization, model training, and interpreting regression results.

---

### 02 – Predicting Price with Location

Explores the relationship between apartment prices and geographic location. This notebook introduces location-based features, missing value imputation, and machine learning pipelines to improve predictive performance.

---

### 03 – Predicting Price with Neighborhood

Focuses on using neighborhood information as a predictive feature. This notebook introduces categorical data encoding through **One-Hot Encoding**, applies **Ridge Regression**, and examines feature importance to better understand how different neighborhoods influence housing prices.

---

### 04 – Predicting Price with Everything

Combines all relevant property characteristics into a comprehensive regression model. This notebook integrates feature engineering, preprocessing, machine learning pipelines, and model evaluation to build the most accurate price prediction model developed throughout the module.


## Skills Developed

Throughout this module, I strengthened both my technical and analytical skills by building machine learning models using real-world housing data. The key skills developed include:

### Data Preparation

- Cleaning and preparing datasets for machine learning.
- Handling missing values using data imputation techniques.
- Removing outliers to improve data quality.
- Selecting relevant features for predictive modeling.
- Preparing training and testing datasets.

### Feature Engineering

- Engineering predictive features from housing data.
- Working with geographic coordinates.
- Encoding categorical variables using **One-Hot Encoding**.
- Identifying and selecting informative predictors.

### Machine Learning

- Building **Linear Regression** models.
- Building **Ridge Regression** models.
- Constructing machine learning pipelines.
- Evaluating regression models using **Mean Absolute Error (MAE)**.
- Interpreting regression coefficients and feature importance.

### Python & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook


## Tools & Technologies

The following tools and technologies were used throughout this module:

| Tool / Technology | Purpose |
|-------------------|---------|
| **Python** | Primary programming language used for machine learning and data analysis. |
| **Pandas** | Data cleaning, transformation, feature engineering, and dataset manipulation. |
| **NumPy** | Numerical computations and array operations. |
| **Matplotlib** | Creating visualizations to explore data and interpret model performance. |
| **Scikit-learn** | Building preprocessing pipelines, regression models, and evaluating predictive performance. |
| **Jupyter Notebook** | Developing, documenting, and presenting the complete machine learning workflow. |


## Repository Structure

```text
Buenos-Aires-Housing-Price-Prediction/
│
├── data/
│   ├── buenos-aires-train.csv
│   ├── buenos-aires-test.csv
│   └── ...
│
├── notebooks/
│   ├── 021-price_and_size.ipynb
│   ├── 022-Predicting-Price-with-Location.ipynb
│   ├── 023-Predicting-Price-with-Neighborhood.ipynb
│   └── 024-price-and-everything.ipynb
│
├── README.md
├── requirements.txt
└── LICENSE
```

## Module Outcomes

By completing the Buenos Aires Housing Price Prediction module, I gained practical experience in applying supervised machine learning techniques to real-world housing data. The module strengthened my understanding of the complete regression modeling workflow, from preparing raw datasets to building, evaluating, and interpreting predictive models.

Some of the key outcomes include:

- Developing confidence in preparing datasets for supervised machine learning.
- Applying feature engineering techniques to improve predictive performance.
- Building and evaluating **Linear Regression** and **Ridge Regression** models.
- Constructing reusable machine learning pipelines using **Scikit-learn**.
- Comparing the predictive power of apartment size, location, and neighborhood information.
- Interpreting model coefficients and feature importance to better understand housing price predictions.
- Building a strong foundation for more advanced machine learning and predictive analytics.


## 👤 Author

**Alice Mercy Wanjiru Koinange**

Statistics & Programming Student | Aspiring Data Analyst

This repository is part of my learning journey through the **WorldQuant Applied Data Science Lab**, where I continue to build practical skills in Python, machine learning, regression modeling, and predictive analytics using real-world housing datasets.

**GitHub:** https://github.com/Koinange-DataScience