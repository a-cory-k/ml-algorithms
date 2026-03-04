# ml-algorithms
# Titanic Survival Prediction

This project predicts Titanic passenger survival using machine learning models.

Two algorithms were implemented: **Decision Tree** and **k-Nearest Neighbors (kNN)**.  
Hyperparameters were tuned using cross-validation.

The final model is **kNN (n_neighbors=8, metric=manhattan)** with accuracy around **78–81%** on unseen data.

Libraries used: pandas, numpy, scikit-learn, seaborn, matplotlib.


# Life Expectancy Prediction

This project predicts **Life expectancy** using machine learning regression models.

The dataset contains socioeconomic and health indicators (WHO data, 2000–2015).  
Preprocessing includes handling missing values (median), encoding categorical variables, and mapping **Country → Continent** with one-hot encoding.

Models implemented: **Ridge Regression**, **k-Nearest Neighbors (kNN)**, and a custom **Random Forest**.  
Hyperparameters were tuned using cross-validation.

The final model is **Random Forest (n_estimators=100, max_depth=20, max_samples=1.0)** with **RMSE ≈ 1.8–1.9** on unseen data.  
Libraries used: pandas, numpy, scikit-learn, seaborn, matplotlib.
