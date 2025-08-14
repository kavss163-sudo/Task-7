# Task-7
Task 7 – Breast Cancer Classification using SVM

This task implements a Support Vector Machine (SVM) model to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin dataset. It includes data preprocessing, feature scaling, training with both linear and RBF kernels, and hyperparameter tuning using GridSearchCV to improve model performance. 

Process Overview

1. Import Libraries – Load required Python libraries (pandas, numpy, matplotlib, and scikit-learn).

2. Load Dataset – Read the breast-cancer.csv file into a pandas DataFrame.

3. Data Preprocessing - Convert the target column diagnosis into binary values (M = 1, B = 0) , Drop unnecessary columns such as id.

4. Feature & Target Separation – Store predictor variables in X and target variable in y.

5. Train-Test Split – Split the dataset into training (80%) and testing (20%) sets.

6. Feature Scaling – Standardize features using StandardScaler to improve SVM performance.

7. Model Training

    Linear Kernel SVM – Train and predict using a linear kernel.

    RBF Kernel SVM – Train and predict using a radial basis function kernel.

8. Model Evaluation – Compare accuracy and classification reports for both kernels.

9. Hyperparameter Tuning – Use GridSearchCV to find the best values for C and gamma for the RBF kernel.

10. Final Model – Retrain SVM using the best parameters and evaluate on the test set.

Key Learning Outcomes

1. Understanding SVM kernels and their effect on classification.

2. Importance of feature scaling in SVM.

3. Practical application of GridSearchCV for model optimization.

4. Comparison of model performance before and after tuning.
