# Prudential Automated Decision System (ADS) Technical Audit

## Overview
This project presents a comprehensive technical audit of Prudential's Automated Decision System (ADS), which uses advanced data analytics and machine learning to revolutionize life insurance risk assessment. Developed in response to a Kaggle competition by Prudential, the ADS implementation leverages ridge regression to predict risk scores for life insurance policies.

## Objective
The ADS aims to streamline the life insurance application process, which traditionally involves extensive client information gathering, medical exams, and long waiting periods for quotes. Our solution offers a more efficient, less labor-intensive, and unbiased method for obtaining life insurance quotes, aligning with modern expectations of instant service and data privacy standards.

## Implementation
- **Input Data**: Utilizes a dataset of 59,381 individual records with 128 columns covering demographic, employment, insurance history, family history, and medical information.
- **Modeling Approach**: Employs Ridge Regression models for prediction, focusing on minimizing the mean squared error (MSE) and ensuring fair and unbiased assessments across various sub-populations.
- **Performance Evaluation**: Analyses include Root Mean Square Error (RMSE) metrics across different subpopulations (age, height, weight, BMI) and fairness assessments using demographic parity and equalized odds metrics.

## Outcomes
- The model exhibits varying performance across different subpopulations, indicating the need for further research and improvements.
- Demographic parity analysis reveals disparities in positive prediction rates across subpopulations, highlighting fairness issues in the ADS.

## Future Directions
- Employ advanced methods like SHAP (SHapley Additive exPlanations) to better understand model predictions, identify potential biases, and improve performance.
- Explore more complex model selections to enhance robustness and accuracy.

## Authors
- Amando Xu (acx202@nyu.edu)
- Rohan Mukerji (rm5176@nyu.edu)

## Acknowledgments
Special thanks to Prudential and the Kaggle community for providing the data and platform for this innovative project.
