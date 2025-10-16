**Gisma Airline's Passengers Satisfaction - Classification Model**
Predict Passenger Satisfaction by Applying Classification Models to Airline Customer Satisfaction Dataset from Kaggle.

📂 Project Overview
Goal: Predict Passenger Satisfaction to help identify which factors will best make a passenger satisfied.
Data: Kaggle – Airline Customer Satisfaction (129,880 rows, 22 features).
Methods: Data Cleaning and Pre-processing, Feature Engineering, Classification Models, Hyperparameter Tuning, Model Evaluation
Outcome: Best model (Random Forest) → Accuracy: 95.8%, ROC-AUC: 0.99, F1-score: 0.96.

🗃️ Dataset
Source: [https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand](https://www.kaggle.com/datasets/raminhuseyn/airline-customer-satisfaction/data)
Target: Satisfaction (0/1)

🧭 Methods
1. Pre-processing (Inconsistent Formats, Missing Values, Outliers)
2. Feature Engineering (created New Features for interpretability, Encoding, Log Transform, Scaling, Feature Selection, Correlation Analysis, Dimension Reduction) 
3. Classification Models (Logistic Regression, Naive Bayes, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Decision Tree, Ensemble Learning: Random Forest)
4. Hyperparameter Tuning (GridSearch)
5. Evaluation Metrics (Accuracy, ROC Curve, Precision, Recall, F1-Score)
6. Feature Importance

🥇 Results
Best: Random Forest
Test: Accuracy: 95.8%, ROC-AUC: 0.99, F1-score: 0.96
Insights: Top 5 most important feature in predicting passenger satisfaction: seat comfort, inflight entertainment, either business/personal travel, baggage handling, and online support. From these we can say that to boost satisfaction the focus should be on operational (in-flight) services rather than flight delays.
