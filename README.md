# Bio-Signal Analysis for Smoking Classification 🚬🧬

This project tackles a real-world machine learning case study to **predict smoking status** using an individual's bio-signals. As a data scientist at a global organization, your mission is to develop a robust model that identifies smokers and non-smokers with high accuracy using physiological indicators.

---

## 🧠 Problem Statement

Predict whether a person is a smoker or not using bio-signal data (e.g., blood metrics, hearing levels, eyesight, etc.). This project involves:
- Cleaning and understanding a medical dataset
- Performing EDA to uncover patterns
- Engineering features for modeling
- Comparing **Logistic Regression**, **Decision Tree**, and **Random Forest**
- Selecting the best-performing algorithm based on accuracy and interpretability

---

## 🗃️ Dataset

The dataset contains **55,692 observations** and **27 features**, including:
- Demographics: `gender`, `age`, `height`, `weight`, `waist`
- Vitals & Lab tests: `blood pressure`, `cholesterol`, `AST`, `ALT`, `GTP`, etc.
- Categorical features: `oral`, `dental caries`, `tartar`
- Target variable: `smoking` (0 = non-smoker, 1 = smoker)

No missing or duplicate records were found during data preprocessing.  

---

## 📊 Key Steps

### ✔️ 1. Preprocessing & Feature Engineering
- Drop non-informative columns (`ID`)
- One-hot encode categorical variables
- Normalize numerical features using `StandardScaler`
- Detect class imbalance (handled if necessary)

### ✔️ 2. Exploratory Data Analysis (EDA)
- Class distribution
- Feature distributions & correlations
- Visual insights using seaborn & matplotlib

### ✔️ 3. Model Building & Evaluation
Implemented and compared three models:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**

Performance metrics:
- Accuracy
- Precision / Recall / F1-score
- Confusion matrix
- Feature importance

### ✔️ 4. Conclusion
The model with the best optimum Accuracy(83%), was selected for future deployment.

---

## 🔍 Future Work
- Hyperparameter tuning using GridSearchCV
- Cross-validation and model ensembling
- Deploy the best model using Flask/Streamlit
- Interpretability tools like SHAP or LIME

---

## 📁 Project Structure

```bash
📂 Bio_Signal_Analysis/
├── Bio_Signal_Analysis.ipynb      # Jupyter notebook with all analysis
├── smoking.csv                    # Raw dataset
└── README.md                      # Project documentation
