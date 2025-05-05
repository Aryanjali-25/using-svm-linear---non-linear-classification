# using-svm-linear-non-linear-classification
# Heart Disease Prediction using SVM

This project uses Support Vector Machines (SVM) for predicting heart disease based on a dataset. The goal is to train an SVM model, visualize the decision boundary, tune hyperparameters, and evaluate the performance of the model using cross-validation.

## Steps:

### 1. Load and Prepare Dataset

-- The dataset is loaded and preprocessed. It consists of features related to heart disease diagnosis (e.g., age, cholesterol levels, etc.).
--It is a binary classification problem where the output is either "Disease" or "No Disease".

### 2. Train SVM with Linear and RBF Kernels

--Two SVM models are trained using different kernels:

--Linear Kernel: Works well when data is linearly separable.
--RBF (Radial Basis Function) Kernel: Suitable for non-linear data.

### 3. Visualize Decision Boundary

 -- A 2D plot is created to visualize how the SVM model separates the data into two classes (disease vs no disease).
 -- This is done for easier understanding of how the classifier makes its decision.

### 4. Tune Hyperparameters (C and Gamma)

 -- "C": Controls the trade-off between maximizing the margin and minimizing the classification error.
 -- "Gamma": Defines the influence of each training point. Higher gamma means closer influence, while lower means 
    broader influence.
 -- We experiment with different values for both to improve model accuracy.

### 5. Cross-Validation for Performance Evaluation

 --The model’s performance is evaluated using 'cross-validation' to ensure the results are reliable and generalizable.
 --It helps in assessing how well the model performs on unseen data.

## Libraries Used:

 "scikit-learn" for machine learning models.
 "matplotlib" for visualization.
 "numpy" for numerical operations.
