# Life Expectancy Prediction

## Overview
This repository contains a comprehensive machine learning project to predict life expectancy using socio-economic, health-related, and demographic data. The project applies advanced data preprocessing, feature engineering, and modeling techniques to achieve high accuracy and robustness in predictions.

---

## Key Highlights

### 1. Comprehensive Exploratory Data Analysis (EDA)
- In-depth visualizations to uncover trends, patterns, and correlations in the data.
- Identification of feature relationships and data distributions.

### 2. Advanced Feature Engineering
- **Handling Missing Values**:
  - Leveraged the **MICE (Multivariate Imputation by Chained Equations)** algorithm for imputing missing data.
  - Categorized missing values where applicable to retain contextual meaning.
- **Skewness Correction**:
  - Used **Yeo-Johnson Transformation**, an extension of Box-Cox, to handle both positive and negative skewness in data.

### 3. Robust Data Splitting and Validation
- Applied **Time Series Cross-Validation** to ensure reliable model evaluation on temporal data.
- Designed an appropriate train-test split strategy to prevent data leakage.

### 4. Machine Learning Techniques
- Explored and compared various models using **Grid Search** and **Cross Validation**, selecting **LightGBM (Gradient Boosting Machine)** as the best-performing model.
- Achieved **MAE of 1.35**, indicating accurate predictions with minimal error.

### 5. Key Metrics
- **MAE (Mean Absolute Error):** 1.3578
- **MSE (Mean Squared Error):** 3.6853
- **RMSE (Root Mean Squared Error):** 1.9197

---
## Future Enhancements
1. Incorporate additional data sources to improve prediction accuracy.
2. Apply advanced hyperparameter optimization techniques.
3. Utilize explainability tools (e.g., SHAP) to interpret model predictions.

---

## Contributing
Contributions are welcome! If you'd like to suggest improvements or report issues, please open an issue or submit a pull request.

