# Credit Card Fraud Detection

This project implements a **Credit Card Fraud Detection system** using machine learning techniques on transaction data.  
The goal is to identify fraudulent transactions with high accuracy while minimizing false positives.

---

## 📌 Project Overview
Credit card fraud is a significant problem in the financial industry.  
This notebook explores fraud detection using machine learning algorithms on the **Credit Card Fraud Detection dataset** (commonly used from Kaggle).

Key steps in the workflow:
1. Data loading and preprocessing  
2. Handling class imbalance (fraud vs. genuine)  
3. Exploratory Data Analysis (EDA)  
4. Model training (using machine learning algorithms)  
5. Model evaluation with metrics suitable for imbalanced datasets  

---

## ⚙️ Tech Stack
- **Python**
- **Jupyter / Google Colab**
- **Pandas, NumPy, Matplotlib, Seaborn** (data processing & visualization)
- **Scikit-learn** (ML models, evaluation)
- **Imbalanced-learn (SMOTE/undersampling techniques)**

---

## 🚀 How to Run

### Option 1: Run in Google Colab
1. Open the notebook in Colab  
2. Upload the dataset (`creditcard.csv`)  
3. Run cells step by step  

### Option 2: Run Locally
```bash
# Clone this repository
git clone https://github.com/Naveensaikumar09/Creditcard_Fraud_detection.git
cd Creditcard_Fraud_detection

# Install dependencies
pip install -r requirements.txt   

# Open the notebook
jupyter notebook "Creditcard Fraud detection.ipynb"
