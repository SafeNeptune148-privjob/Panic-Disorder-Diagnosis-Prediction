# Panic-Disorder-Diagnosis-Prediction
This project uses real-world data and several ML models (Random Forest, XGBoost, Logistic Regression, Clustering) to predict whether an individual is likely to suffer from Panic Disorder, a psychological condition that’s often hard to diagnose early.

 #####Motivation:
Diagnosing panic disorders is difficult, but early detection can save lives. This project aims to support medical professionals through data-driven prediction and insights.

 ######Dataset:
Sourced from [Kaggle](#), containing 100,000+ instances with medical, demographic, and psychological features.

#####Exploratory Data Anlysis:
[Exploratory Data Analysys notebook](./Exploratory_Data_Analysis.ipynb)

 #####Models Used:
- Random Forest
  [Data Preprocessing for Random Forest](./Preprocessing_module.ipynb)
  [Notebook Random Forest](./Random_forest_intento_1.ipynb)
- XGBoost
  [Notebook XGBoost](./XGBOOST_model.ipynb)
- Logistic Regression
  [Notebook Logistic Regression](./Logistic_model.ipynb)
- Hierarchical Clustering (Gower + T-SNE)
  [Notebook Clustering](./Hierarchical_GowersD.ipynb)
  
 #####Key Results:
- XGBoost Accuracy: **0.99**, 0 False Negatives
- Insightful clusters found using Gower distance

# Please Check the full report below!!
[📄 View Full Report (PDF)](./Anxiety_disorder_report.pdf)
