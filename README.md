# E-Commerce Pricing Optimization Analysis

An end-to-end data analysis and machine learning project exploring what drives 
customer purchase behavior and how pricing decisions can be optimized to improve 
conversion and margin performance.

## Project Overview
This analysis was completed as part of a data analytics exercise using a 2,044 
row e-commerce transaction dataset. It covers exploratory data analysis, feature 
engineering, predictive modeling, and price point simulation.

## Key Findings
- Review Rating is the strongest driver of purchase probability (49.4% feature importance)
- Effective Price is the second most important factor (23.5% feature importance)
- Logistic Regression achieved 99.5% accuracy and a perfect AUC of 1.0
- Price simulation identified a concrete price ceiling of $349.66 for the sample transaction tested

## Files
- `index.html` — full analysis rendered as a webpage
- `pricing_analysis.ipynb` — Jupyter notebook with all code and explanations
- `dataset.csv` — raw dataset used in the analysis

## Requirements
pandas, numpy, matplotlib, seaborn, scikit-learn 1.5.2

Install with: `pip install pandas numpy matplotlib seaborn scikit-learn`
