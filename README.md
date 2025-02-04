# ML-project-
Overview
This project analyzes hotel booking cancellations using machine learning models to predict the likelihood of cancellations. By leveraging structured data from Kaggle, this study explores factors influencing cancellations and builds predictive models to help hotels optimize resource allocation and minimize revenue loss.

Project Components
Reports: A detailed analysis of the dataset, preprocessing techniques, model selection, and evaluation.
Notebook: A Jupyter Notebook implementing data cleaning, feature engineering, model training, and performance comparison.

Dataset
The dataset consists of 119,390 hotel booking records with features such as:
Booking details (lead time, reservation status)
Guest demographics (country, customer type)
Stay details (number of nights, room type)
Revenue-related attributes (average daily rate, deposit type)

Methodology
1. Exploratory Data Analysis (EDA)
Identified key cancellation factors (lead time, deposit type, market segment).
Used visualizations (heatmaps, histograms, box plots) to detect patterns and outliers.
2. Machine Learning Models
Logistic Regression: Provides interpretability and baseline performance.
Gradient Boosting Machines (GBM): Captures complex, non-linear relationships.
XGBoost: Achieves high accuracy and robustness in cancellation prediction.
3. Model Evaluation
Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
Comparison of models before and after hyperparameter tuning.
Principal Component Analysis (PCA) for dimensionality reduction.

