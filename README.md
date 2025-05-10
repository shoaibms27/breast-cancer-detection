# breast-cancer-detection


This project uses a Logistic Regression model to predict whether a tumor is **benign** or **malignant** based on various medical features extracted from breast cancer biopsies.

---

## 📌 Problem Statement

Early detection of breast cancer is crucial for effective treatment. This project builds a **classification model** using machine learning techniques to assist in diagnosing breast cancer.

---

## 🚀 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (Logistic Regression, GridSearchCV)
- Matplotlib & Seaborn (for EDA and visualization)
- Pickle (for saving the model)

---

## 📊 Dataset

The dataset used is the **Breast Cancer Wisconsin Diagnostic Dataset**, available from `sklearn.datasets.load_breast_cancer()` or from CSV.

Each sample contains features like:
- `radius_mean`, `texture_mean`, `perimeter_mean`, ...
- Diagnosis label: `M` (malignant) or `B` (benign)

---

## ✅ Workflow

1. Load and clean the data
2. Exploratory Data Analysis (EDA)
3. Feature scaling using `StandardScaler`
4. Model building using `LogisticRegression`
5. Hyperparameter tuning using `GridSearchCV`
6. Evaluation using accuracy and confusion matrix
7. Save the model using `pickle`

---

## 📈 Model Performance

- **Best Parameters:** `C=10`, `penalty='l1'`, `solver='liblinear'`
- **Cross-Validation Accuracy:** 97.58%
- **Test Accuracy:** ~97–98%

---

## 🛠️ How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/breast-cancer-detection-ml.git
   cd breast-cancer-detection-ml
