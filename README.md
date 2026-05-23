# IPL Match Outcome Prediction using Machine Learning 🏏📊

This project focuses on predicting IPL match outcomes using Machine Learning and historical IPL match data. The model predicts four match result categories:

* A_big → Team A wins by a big margin
* A_small → Team A wins by a small margin
* B_big → Team B wins by a big margin
* B_small → Team B wins by a small margin

The complete pipeline includes:

* Data cleaning and preprocessing
* Team and venue standardization
* Feature engineering using:

  * Team win percentages
  * Venue strength
  * Toss-based insights
  * Strength difference metrics
* Exploratory Data Analysis (EDA) with visualizations
* LightGBM multiclass classification model
* Probability calibration and ensemble experimentation
* Kaggle competition submission pipeline

The project was built as part of an IPL analytics challenge focused on multiclass log loss optimization and probabilistic forecasting.

## Tech Stack

* Python
* Pandas
* NumPy
* LightGBM
* Scikit-learn
* Matplotlib
* Seaborn

## Key Learnings

* Feature engineering for sports analytics
* Multiclass probability prediction
* Log loss optimization
* Ensemble learning
* Model calibration
* Handling data leakage and distribution shift

This project helped me understand how Machine Learning can be applied beyond traditional datasets — blending cricket analytics, probability, and predictive modeling into a real-world forecasting system 🚀
