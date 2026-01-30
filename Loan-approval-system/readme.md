LoanWise: Loan Approval Prediction
This project focuses on predicting loan eligibility using machine learning classification algorithms. By analyzing applicant data such as income, credit history, and employment status, the model aims to automate the initial screening process for loan applications.

Project Overview
The primary objective is to build a robust classification model that can determine whether a loan application should be approved or rejected. The project explores various algorithms, from baseline linear models to ensemble methods, to identify the most accurate predictor.

Key Features
Exploratory Data Analysis (EDA): Visualization of demographic distributions (Gender, Education, etc.) and financial trends using Seaborn and Matplotlib.

Data Preprocessing: - Handling missing values via Mean and Most Frequent imputation strategies.

Feature scaling using StandardScaler for distance-based models.

Categorical encoding using LabelEncoder and OneHotEncoder.

Comprehensive Modeling: Implementation of multiple classifiers to compare performance.

Evaluation: Detailed performance analysis using Precision, Recall, F1-Score, and Confusion Matrices.

Dataset
The model is trained on a loan approval dataset containing the following attributes:

Demographics: Gender, Age, Marital Status, Education.

Financials: Applicant Income, Co-applicant Income, Loan Amount, Credit Score.

Employment: Employment Status, Work Experience.

Target: Loan_Approved (Binary: Yes/No).

Technologies Used
Language: Python

Libraries:

pandas & numpy: Data manipulation

scikit-learn: Machine learning and preprocessing

seaborn & matplotlib: Data visualization

Models Implemented
The following algorithms are utilized within the notebook:

Logistic Regression

K-Nearest Neighbors (KNN)

Gaussian Naive Bayes

Performance Summary (Naive Bayes)
Based on the final evaluation in the notebook, the Naive Bayes model achieved:

Accuracy: 86.5%

Precision: 80.36%

Recall: 73.77%

F1 Score: 76.92%

How to Use
Prerequisites: Ensure you have Python installed along with the libraries listed in the Technologies section.

Dataset: Place the loan_approval_data.csv in the same directory as the notebook.

Execution: Open loan_wise.ipynb in a Jupyter environment or VS Code and run the cells sequentially to reproduce the results.
