

# Medical Insurance Premium Predictor

An interactive machine learning pipeline that predicts individual annual medical insurance costs based on demographic and lifestyle factors. This project compares standard regression algorithms and includes an interactive calculator widget running directly in the browser.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sibgat-git/Medical-Insurance-Premium-Predictor/blob/main/Medical_Insurance_Premium_Predictor_.ipynb)

## Key Insights & Business Findings
- Smoking Status is the single largest driver of healthcare costs, adding an average flat premium of ~$23,296/year.
- Age and BMI scale premiums incrementally, with higher BMI showing a compounding effect for smokers.
- Model Performance Optimization:
  - Linear Regression (Baseline): Explains ~82.3% of the variance.
  - Random Forest Regressor: Captures non-linear feature interactions to achieve higher overall accuracy.

## Tech Stack & Libraries
- Language: Python 3
- Data Analysis & Visualization: Pandas, NumPy, Seaborn, Matplotlib
- Machine Learning: Scikit-Learn (Linear Regression, Random Forest Regressor, Train-Test Split, Model Metrics)
- Interactive UI: Google Colab Widgets & Sliders

## How to Run the Project
1. Click the "Open in Colab" badge at the top of this page.
2. Once the notebook opens in Google Colab, upload the insurance.csv file to the session workspace.
3. Go to the top menu and click Runtime > Run all.
4. Scroll to the bottom to interact with the live Premium Calculator and estimate insurance premiums with custom parameters!
