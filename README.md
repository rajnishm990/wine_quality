# Wine Quality Analysis

This repository contains a Jupyter Notebook where quality analysis of wine is conducted using machine learning techniques. The notebook covers exploratory data analysis (EDA), model selection, and evaluation.

## Dataset Description

The dataset consists of features representing the chemical properties of wine and the target variable is the quality of the wine on a 10-point scale. Here is a glimpse of the dataset:

| Fixed Acidity | Volatile Acidity | Citric Acid | Residual Sugar | Chlorides | Free Sulfur Dioxide | Total Sulfur Dioxide | Density | pH | Sulphates | Alcohol | Quality |
|---------------|------------------|-------------|----------------|-----------|---------------------|----------------------|---------|----|-----------|---------|---------|
| 7.4           | 0.70             | 0.00        | 1.9            | 0.076     | 11.0                | 34.0                 | 0.9978  | 3.51| 0.56      | 9.4     | 5.0     |
| 7.8           | 0.88             | 0.00        | 2.6            | 0.098     | 25.0                | 67.0                 | 0.9968  | 3.20| 0.68      | 9.8     | 5.0     |
| 7.8           | 0.76             | 0.04        | 2.3            | 0.092     | 15.0                | 54.0                 | 0.9970  | 3.26| 0.65      | 9.8     | 5.0     |
| 11.2          | 0.28             | 0.56        | 1.9            | 0.075     | 17.0                | 60.0                 | 0.9980  | 3.16| 0.58      | 9.8     | 6.0     |
| 7.4           | 0.70             | 0.00        | 1.9            | 0.076     | 11.0                | 34.0                 | 0.9978  | 3.51| 0.56      | 9.4     | 5.0     |

## Analysis Summary

- **Imbalance**: The dataset suffers from class imbalance, meaning there are unequal instances for each quality rating.
- **Feature Correlation**: Highly correlated features include:
  - Fixed Acidity and Citric Acid (0.67)
  - Free Sulfur Dioxide and Total Sulfur Dioxide (0.67)
  - Fixed Acidity and Density (0.67)
- **Best Performing Model**: The Random Forest Classifier yielded the best performance for this dataset.

## Models Evaluated

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- CatBoost
- Support Vector Classifier (SVC)

## Results

The Random Forest Classifier outperformed other models with an accuracy of X%.

## Future Scope or Advancements

- **Feature Engineering**: Explore additional features or transformations to enhance model performance.
- **Imbalance Handling**: Implement techniques like oversampling or undersampling to address class imbalance.
- **Hyperparameter Tuning**: Fine-tune model parameters for better performance.
- **Ensemble Methods**: Experiment with ensemble methods like stacking or boosting to further improve model accuracy.
- **Deployment**: Deploy the best-performing model as a service for real-time predictions.

## Results

The Random Forest Classifier outperformed other models .

## Usage

1. Clone this repository.
2. Install the required dependencies specified in `requirements.txt`.
3. Open and run the Jupyter Notebook `wine_quality_analysis.ipynb`.
4. Follow along with the analysis, model selection, and evaluation steps.
