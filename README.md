# Task-4
# 🧪 Breast Cancer Prediction - Logistic Regression

This project is part of **Task 4** from the machine learning track. It uses the **Breast Cancer Wisconsin Dataset** to perform binary classification and predict whether a tumor is malignant or benign using logistic regression.

---

## 📌 Dataset Overview

- **Dataset:** Breast Cancer Wisconsin Dataset
- **Source:** [Click here to download dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Shape:** 569 samples × 32 features
- **Target:** `diagnosis` (B = Benign, M = Malignant)

---

## ✅ Steps Performed

### 1. 📦 Data Loading & Cleaning
- Loaded the dataset using pandas.
- Checked for **null values**.
- Dropped the unnecessary column: `Unnamed: 32`.

### 2. ✂️ Train-Test Split & Standardization
- Encoded the `diagnosis` column into 0 (Benign) and 1 (Malignant).
- Split the dataset using `train_test_split()` (80% train / 20% test).
- Standardized the features using `StandardScaler`.

### 3. 🧠 Logistic Regression Model
- Fitted a `LogisticRegression()` model on the training data.
- Used `.predict()` to generate predictions on the test set.

### 4. 📈 Evaluation
- Evaluated using:
  - **Confusion Matrix**
  - **Precision**
  - **Recall**
  - **F1 Score**
  - **ROC-AUC Score**
- Visualized the confusion matrix and ROC curve.

### 5. 🎯 Threshold Tuning & Sigmoid
- Explained how logistic regression uses the **sigmoid function** to output probabilities.
- Tuned classification threshold to analyze prediction confidence.

---

## 🔍 Model Testing & Results

- Compared `Predicted` vs `Actual` values.
- Measured **accuracy** by counting correct predictions.
- Visual comparison with:
  - Pandas DataFrame of predictions
  - Count plots using Seaborn

---

## 📊 Key Takeaways

- Logistic regression can effectively predict binary outcomes.
- Evaluation metrics give a clear idea about model performance.
- Visualizations help explain prediction power across genders and tumor characteristics.

---

## 👩‍💻 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

---

## 📌 Author

- **Puli Bharat**  
- Machine Learning Enthusiast  
- 🐍 Python | 🤖 ML | 📊 Data Science  
