# Task4_ElevateLabs
# Logistic Regression — Breast Cancer Classification

## 📌 Objective

The objective of this task is to build a **binary classification model** using Logistic Regression.
The model predicts whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)** based on medical features.

---

## 🛠 Tools & Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

Breast Cancer Wisconsin Dataset (from Scikit-learn)

The dataset contains cell nucleus measurements such as:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Fractal Dimension

**Target Variable**

* 0 → Malignant (Cancer)
* 1 → Benign (No Cancer)

---

## 🔎 Steps Performed

### 1. Data Loading

* Loaded dataset using `sklearn.datasets`
* Converted to Pandas DataFrame

### 2. Data Preprocessing

* Split dataset into features and target
* Performed train-test split (80-20)
* Standardized features using StandardScaler

### 3. Model Training

* Implemented Logistic Regression model
* Trained using training data

### 4. Prediction

* Predicted class labels
* Predicted probabilities using sigmoid function

### 5. Model Evaluation

Evaluated using:

* Confusion Matrix
* Precision
* Recall
* F1 Score
* ROC-AUC Curve

---

## 📊 Results

| Metric    | Value   |
| --------- | ------- |
| Accuracy  | ~97%    |
| Precision | ~97–98% |
| Recall    | ~95–99% |
| F1 Score  | ~0.97   |
| ROC-AUC   | ~0.997  |

---

## 📈 Interpretation

* High recall ensures cancer cases are rarely missed
* High precision avoids false alarms
* ROC-AUC near 1 indicates excellent class separation

---

## 🧠 Interview Questions

**1. Logistic vs Linear Regression**
Linear predicts continuous values, logistic predicts probability for classification.

**2. Sigmoid Function**
Converts linear output into probability between 0 and 1.

**3. Precision vs Recall**
Precision measures correctness of positive predictions, recall measures how many actual positives were detected.

**4. ROC-AUC Curve**
Measures model’s ability to distinguish between classes.

**5. Confusion Matrix**
Shows true vs predicted classifications.

**6. Imbalanced Classes**
Model may bias toward majority class.

**7. Threshold Selection**
Default is 0.5 but can be adjusted depending on problem.

**8. Multi-class Logistic Regression**
Yes, using One-vs-Rest strategy.

---

## 🏁 Conclusion

The Logistic Regression model achieved high accuracy and ROC-AUC score, demonstrating excellent classification ability.
The model effectively distinguishes malignant and benign tumors, making it suitable for medical prediction tasks.

---

## 👨‍💻 Author

Mohd Yusuf Khan
