# heartdiseaseUCI
Analysis to predicted heart disease causes with machine learning algorithm
by Mochamad Derisman Nugraha

from Public Health dataset ( https://www.kaggle.com/ronitf/heart-disease-uci or https://archive.ics.uci.edu/ml/datasets/Heart+Disease )
## Abstract

Heart disease, otherwise known as cardiovascular disease, covers a wide range of conditions that affect the heart and has been the leading cause of death worldwide over the past few decades. This relates to the many risk factors for heart disease and the need for time to obtain an accurate, reliable and reasonable approach to making an early diagnosis to achieve rapid disease management. Data mining is a commonly used technique for processing very large data in the healthcare domain. The researchers applied several data mining and machine learning techniques to analyze huge complex medical data, helping healthcare professionals to predict heart disease 

Dataset is known to be unbalanced (oversampling), the author performs an imbalance oversampling treatment for effectively run machine learning algorithm. The results of research conducted to predict heart disease and its causes. from the modeling carried out including Logistic Regression, Naive Bayes, Support Vector Machine, K-Nearest Neighbors, Decision Tree, and Random Forest. The modeling results above show that Random Forest has the most significant accuracy of all the modeling algorithms had > 90% accuracy score, and average Cross Validation with 10 Folds have scores 84.79% 

Next, the authors carry out further evaluations using Random Forest with hyperparameter instrument Random state: 10 , max depht: 15, max feature: log2, sample leaf: 3, sample split: 10 and estimators: 15, and criterion entropy. The Accuracy increase 95.08 %. in predicting and knowing the cause of heart disease by the existing sample data with using the Permutation Importance and SHAP methods, known that from the entire sample it shows CA(major blood vessels), Chest Pain: Typical Angina, Thal (thalassemia fixed and reversable defect) and Oldpeak (Max Heart Rate) as an influential factors causing heart disease. 

For recommendations of the 5 influential variables, a cardiologist should diagnose these variables early so that the treatment of heart disease patients is more effective and efficient.
