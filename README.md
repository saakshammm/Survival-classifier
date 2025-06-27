
## 🎯 Objective

To build and evaluate a binary classifier using logistic regression.  
Target variable: `Survived` (0 = No, 1 = Yes)

---

## 🛠 Tools & Libraries

- Python 🐍
- Pandas & NumPy
- Scikit-learn (LogisticRegression, metrics, train_test_split)
- Matplotlib & Seaborn (for ROC curve and sigmoid visualization)

---

## 📊 Steps Performed

1. **Loaded pre-cleaned Titanic dataset**
2. **Split** data into training and test sets
3. **Standardized** features using `StandardScaler`
4. **Trained** a Logistic Regression model (`sklearn.linear_model`)
5. **Evaluated** performance using:
   - Confusion Matrix
   - Precision & Recall
   - ROC-AUC Score
6. **Plotted**:
   - ROC Curve
   - Sigmoid Function for interpretation

---

## 📈 Results

- The model learned to distinguish between survived vs not-survived passengers.
- Evaluation metrics like precision, recall, and ROC-AUC were used to measure performance.
- Sigmoid curve helped visualize how logistic regression turns raw scores into probabilities.

---

## 🧠 Key Concepts Practiced

- Binary classification using Logistic Regression
- Model evaluation using classification metrics
- Importance of decision thresholds
- Visual interpretation of model output

---

## 📁 Files Included

- `cleaned_data.csv` – My preprocessed Titanic dataset
- `Binary.ipynb` – Code & plots
- `README.md` – This file

---
