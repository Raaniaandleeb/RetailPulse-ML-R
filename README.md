# RetailPulse-ML-R

## What is this project?

RetailPulse-ML-R is a real-world retail data analysis and machine learning
project using the UCI Online Retail dataset.

The project analyzes customer purchasing behavior, sales performance,
customer segments, and future purchase probability using R.

## Why was this project created?

The main goal is to understand how data can be used to:

- Analyze retail sales and customer behavior
- Identify valuable customer segments
- Understand purchasing patterns
- Predict whether customers are likely to purchase again
- Apply statistical analysis and machine learning to a real-world dataset

## Who is this project for?

This project was developed as a practical data science and machine learning
portfolio project by Raania Andleeb.

It demonstrates the use of R, data analysis, visualization, customer
segmentation, and supervised machine learning on real-world business data.

## What was done?

The project includes:

- Data cleaning and preparation
- Sales and revenue analysis
- Monthly revenue analysis
- Country-level revenue analysis
- Customer order and revenue analysis
- RFM (Recency, Frequency, Monetary) analysis
- K-Means customer segmentation
- Logistic Regression
- Random Forest
- Model evaluation using Accuracy, Sensitivity, Specificity, Precision,
  F1 Score, ROC and AUC
- Customer purchase probability prediction

## Key Results

- Approximately **£8.91 million** in total revenue
- **18,532** unique orders
- **4,338** unique customers
- UK was the largest revenue market
- RFM clustering identified a small group of extremely high-value customers
- Logistic Regression achieved an AUC of approximately **0.72**
- Random Forest achieved an AUC of approximately **0.71**
- Logistic Regression was selected as the final model

## Tools Used

- R
- RStudio
- Git
- GitHub
- ggplot2
- dplyr
- lubridate
- tidyr
- cluster
- pROC
- randomForest

## Dataset

The project uses the **UCI Online Retail dataset**, containing transaction
records from a UK-based online retailer.

## Project Structure

```text
RetailPulse-ML-R/
├── data/
├── output/
├── plots/
├── script/
│   └── 01_retail_ml.R
├── .gitignore
└── RetailPulse-ML-R.Rproj