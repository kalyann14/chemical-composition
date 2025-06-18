🚿 **Predicting Chemical Reformulation in Cosmetic Products**
This capstone project leverages machine learning to predict chemical reformulation and product discontinuation in cosmetic products, using data from the California Safe Cosmetics Program (CSCP).

🎯 Objectives
1.Predict Reformulation: Identify products likely to undergo reformulation based on ingredient risk and usage patterns.
2.Predict Discontinuation: Forecast product discontinuation driven by regulatory pressure and ingredient concerns.

🧪 Data Source
California Safe Cosmetics Program (CSCP) dataset, 100,000+ product records with chemical, category, and reporting metadata

📈 Methods & Tools
Preprocessing: Python (Pandas, NumPy), Label Encoding, One-Hot Encoding

**EDA**: Seaborn, Matplotlib

**Modeling**: Random Forest, XGBoost, LightGBM

**Evaluation**: Accuracy, F1 Score, Confusion Matrix, ROC-AUC

🔍 Key Results
**Reformulation Prediction:**
Best model: XGBoost with 93% accuracy
Feature importance: Chemical count, cancer-related chemical presence, and product category

**Discontinuation Prediction:**
Best model: Random Forest with 91% accuracy
High-impact features: Chemical risk scores, product type, and report year

📌 Key Takeaways
1.Regulatory signals and chemical risk metrics are strong predictors of reformulation/discontinuation.
2.Feature engineering significantly boosts model accuracy and interpretability.
3.ML can assist in early identification of high-risk products, aiding safer consumer markets.

🔧 Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Matplotlib, Seaborn, Jupyter
