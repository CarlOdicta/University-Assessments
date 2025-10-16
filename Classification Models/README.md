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

🧭 Approach
Cleaning (fix NA, drop invalid rows, remove company)
EDA (lead time distribution, correlation heatmap)
Preprocess (ColumnTransformer: scale num + OHE cat)
Balance (SMOTE)
Modeling (10 NN configs; early stopping)
Evaluation (Accuracy, Precision, Recall, F1; Confusion Matrix)

🥇 Results
Best: Model-8 (256-128-64 + Dropout 0.1 + BatchNorm)
Test: Acc 87.3% • Precision 82.1% • Recall 84.1% • F1 83.1%
Insights: Lead time strongly drives cancellations; ADR has weak correlation.
