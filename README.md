[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rileybarka/Lab-1-Intro-to-ML/blob/main/notebooks/Lab1.ipynb)

# Lab 1: Introduction to Machine Learning

Welcome to Lab 1 of the Fall AI Studio!  
This project introduces core machine learning concepts and workflows using real-world datasets from domains like hospitality, housing, dining, zoology, and transportation.

---

## Datasets Used

| Dataset | Description |
|--------|-------------|
| **Airbnb Listings NYC (Dec 2021)** | Modified dataset of NYC Airbnb listings (price, location, reviews, etc.) |
| **Housing Prices** | Home attributes and sale prices for regression analysis |
| **Restaurant Business Rankings 2020** | Ranked list of top restaurants with metadata for clustering/classification |
| **Zoo Animal Classification** | Categorical data for supervised learning practice |
| **Flight Delay Data** | Delay and schedule info from airlines to practice time-based or binary classification |

---

##  Objectives

- Understand and apply foundational machine learning concepts  
- Explore and preprocess real-world datasets  
- Perform basic classification, regression, and clustering tasks  
- Build comfort with Jupyter/Colab workflows  
- Identify modeling potential in messy and varied data types  

---

##  Methodology

Across the datasets, the following machine learning steps were practiced:

- Exploratory Data Analysis (EDA)  
- Data cleaning and transformation  
- Label encoding and feature scaling  
- ML modeling: Linear Regression, k-Nearest Neighbors, Decision Trees  
- Model evaluation: accuracy, confusion matrix, MAE, RMSE  

Each dataset is explored through individual exercises and Jupyter notebooks.

---

##  Key Findings

- NYC Airbnb prices show high variance and require normalization/log transformation.  
- Housing price predictions benefit from engineered features like square footage per room.  
- Restaurant clustering revealed region-based business similarities.  
- Zoo dataset helped illustrate the difference between binary and multi-class classification.  

---

## Setup Instructions

To run this project:

### Option 1: Open in Google Colab
Click the badge at the top of this README.

### Option 2: Run Locally
```bash
git clone https://github.com/rileybarka/Lab-1-Intro-to-ML.git
cd Lab-1-Intro-to-ML/notebooks
jupyter notebook Lab1.ipynb
