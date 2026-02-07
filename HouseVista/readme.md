# House Price Prediction: Manual vs. Pipeline Workflow

This project demonstrates the transition from a manual machine learning workflow to a professional **Scikit-Learn Pipeline**. 

### 🏠 Project Overview
Using the House Prices dataset, I built a Linear Regression model to predict sales prices. The core focus of this notebook is comparing two different development approaches.

### 🛠️ Key Features
- **Manual Workflow:** Step-by-step data cleaning, imputation, and encoding using Pandas and Scikit-Learn.
- **Pipeline Workflow:** Utilizing `Pipeline` and `ColumnTransformer` to automate:
  - Mean Imputation and Scaling for numeric features (ints & floats).
  - Most Frequent Imputation and One-Hot Encoding for categorical features.
- **Dynamic Feature Selection:** Automatically identifying column types to ensure scalability.

### 📈 Results
Both methods achieved comparable $R^2$ scores, but the Pipeline approach significantly reduced code complexity and eliminated risks of data leakage.

### 🧰 Tech Stack
- Python (Pandas, NumPy)
- Scikit-Learn
- Jupyter Notebooks
