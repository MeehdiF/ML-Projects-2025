House Price Prediction with Regression Models

This project is a machine learning pipeline for predicting house prices using different regression models.
The dataset used is similar to the Kaggle House Prices dataset.

🚀 Project Overview
	•	Goal: Predict the house sale price (SalePrice) based on various house features.
	•	Techniques Used:
	•	Data cleaning & handling missing values with SimpleImputer
	•	Feature encoding for categorical data
	•	Feature selection using:
	•	Random Forest feature importance
	•	Correlation analysis
	•	Recursive Feature Elimination (RFE)
	•	Scaling features using RobustScaler and StandardScaler
	•	Training and comparing 3 models:
	•	Linear Regression
	•	Random Forest Regressor
	•	Gradient Boosting Regressor
	•	Model evaluation using MAE, RMSE, and R²
	•	Residual plots for error analysis

⸻

📊 Results
	•	Models compared: Random Forest, Linear Regression, Gradient Boosting
	•	Best performance achieved with Gradient Boosting (after hyperparameter tuning).
	•	Metrics:
	•	MAE: (example) ~18,000
	•	RMSE: (example) ~25,000
	•	R²: (example) ~0.85

Note: The results may vary depending on the dataset version and parameters.

⸻

🔮 Future Improvements
	•	Use cross-validation instead of a single train-test split
	•	Automate preprocessing with Pipelines
	•	Experiment with XGBoost, LightGBM, CatBoost
	•	Deploy the best model with Flask/FastAPI + Docker

⸻

📌 Author

Developed by Mehdi as part of my journey to become a Machine Learning Engineer 🚀
