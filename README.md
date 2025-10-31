Machine Learning Predictive Modeling – Classification & Regression Tasks
Overview

This project implements and compares multiple machine learning models for classification and regression problems using Python and Jupyter Notebook.
The work was completed as part of the 6006CEM: Machine Learning and Data Mining coursework.

Classification Task: Predict customer churn using telecom data.

Regression Task: Predict medical insurance charges based on demographic and lifestyle factors.

Both tasks include data preprocessing, model training, hyperparameter tuning, evaluation, and explainability analysis (Permutation Importance and Partial Dependence Plots).

Project Structure
├── classification_assignment.ipynb     # Classification task notebook
├── regression_assignment.ipynb          # Regression task notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv # Dataset for classification task
├── insurance.csv                        # Dataset for regression task
└── README.md                            # Project documentation

⚙️ Setup Instructions
1. Install Required Packages

Open a terminal (or Anaconda Prompt) and run:

pip install pandas numpy matplotlib seaborn scikit-learn tensorflow shap


(If you are using Anaconda, most of these packages are already installed.)

2. Launch Jupyter Notebook

Run the following command in your project directory:

jupyter notebook

3. Open and Run the Files
Classification Task

Open classification_assignment.ipynb

Ensure the dataset WA_Fn-UseC_-Telco-Customer-Churn.csv is in the same directory.

Run all cells sequentially to reproduce results and visualizations.

Regression Task

Open regression_assignment.ipynb

Ensure the dataset insurance.csv is in the same directory.

Run all cells sequentially to train and evaluate regression models.

🧪 Models Implemented

Classification Task:

Logistic Regression

Feedforward Neural Network (FNN)

Random Forest

Ensemble (Soft Voting)

Regression Task:

Linear Regression

Feedforward Neural Network (FNN)

Random Forest

📊 Key Outputs

Model comparison tables (Accuracy, F1, ROC-AUC / RMSE, R²)

Confusion matrices and ROC curves

Feature importance and Partial Dependence plots

Interpretability analysis for explainable AI compliance

🧩 Requirements

Python 3.8 or above

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow
