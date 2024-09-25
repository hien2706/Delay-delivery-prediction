# Delay Delivery Prediction

**Objective:** Predict potential delays in deliveries to enable proactive mitigation strategies.

**Approach:**

* **Data Preparation:** Extensive cleaning and EDA to handle missing values, outliers, and ensure data quality.
* **Feature Engineering:** Created new features to capture relevant information and improve model performance.
* **Feature Selection:** Used Information Value to identify the most impactful predictors.
* **Model Development:** Built and optimized LightGBM and CatBoost models using stratified k-fold cross-validation and RandomizedSearchCV.

**Results:**

* Achieved F1-scores of 73% (LightGBM) and 69% (CatBoost) on the test set.

LightGBM confusion matrix:\
Catboost confusion matrix:\
![Catboost confusion](https://github.com/hien2706/Delay-delivery-prediction/blob/main/images/CatBoost_confusion_matrix.jpg)

**Tech Stack:** Python (Pandas, NumPy, Scikit-learn), LightGBM, CatBoost

**Further Exploration:**

* Explore additional feature engineering techniques.
* Experiment with other machine learning algorithms.
* Deploy the model into a production environment for real-time predictions.

