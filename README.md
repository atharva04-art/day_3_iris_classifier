# 🌸 Day 3: Iris Flower Classifier

This project uses the famous **Iris dataset** to build a machine learning model that can classify flowers into:
- Setosa
- Versicolor
- Virginica

### 📦 Tech Used
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn (Logistic Regression)
- Matplotlib (optional for visualization)

---

## 🚀 How It Works

### 1. Load Dataset
Using `load_iris()` from `sklearn.datasets`

### 2. Prepare Data
- Features: Sepal & Petal measurements
- Target: Flower species
- Split: 80% training, 20% testing

### 3. Train Model
```python
from sklearn.linear_model import LogisticRegression
model = LogisticRegression(max_iter=200)
model.fit(X_train, y_train)
