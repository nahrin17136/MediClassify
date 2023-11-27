# MediClassify-A-Generalized-Prediction-Model-for-Multiple-Medical-Datasets-Classification
Fulfilling the critical demand for accurate early disease detection, this project utilizes machine learning (ML) to navigate intricate medical data. The project objective is to pioneer a refined, generalized prediction model, elevating the precision and dependability of classifying prevalent diseases during their initial stages.
#Datasets
Analyzed and evaluated, four datasets sourced from diverse repositories formed the basis for developing the predictive model.
1. MRI and Alzheimer’s Dataset (MAD)
2. SPECTF Heart Dataset (SHD)
3. Early Stage Diabetes Dataset (ESDD)
4. Lower Back Pain Dataset (LBPD)
#Methodology
#Pre-processing Techniques
1. KNN Imputation
2. Label Encoding
3. Standard Scaling
4. SMOTE Sampling (Synthetic Minority Over-Sampling Technique)
#Classification techniques along with hyperparameters tuning
1. Logistic Regression (LR)
2. Support Vector Machine (SVM)
3. Naive Bayes (NB)
4. Decision Tree (DT)
5. Random Forest (RF)
6. Extra Tree (ET)
#Ensemble Techniques
The three best-performing classifiers (LR, RF, and SVM) were selected, and their hyperparameters were used to create an ensemble model through the ensemble technique.
1.Hard Voting
2. Soft Voting
3. Stacking
4. Bagging
5. Boosting
#Results
The proposed generalized stacking ensemble model outperformed all other classifiers.
1. MAD: 96.97%
2. SHD: 95.08%
3. ESDD: 98.90%
4. LBPD: 91.34%

