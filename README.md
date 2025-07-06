## 📄 Summary of Machine Learning Code

This notebook presents a **multiclass classification pipeline** designed to predict football match outcomes using various machine learning models. The workflow includes **data preprocessing**, **model training**, **evaluation**, and **comparison**.

---

### 🔍 Key Steps

#### ✅ 1. Data Preparation
- Selected and cleaned features using `pandas`.
- Encoded categorical variables with `OneHotEncoder` and `OrdinalEncoder`.
- Split dataset into training and test sets using `train_test_split`.

#### ✅ 2. Models Implemented
- **Logistic Regression** – baseline linear model.
- **Decision Tree** – interpretable non-linear model.
- **Random Forest** – ensemble method for generalization.
- **XGBoost** – gradient boosting for high-performance classification.
- **CatBoost** – optimized for categorical features.
- **SVM (LinearSVC)** – effective on linearly separable data.
- **MLPClassifier** – neural network (multilayer perceptron).

#### ✅ 3. Evaluation Metrics
- **Accuracy**
- **Classification Report** (precision, recall, F1-score)
- **Confusion Matrix**
- **ROC AUC** (One-vs-Rest strategy)

---

### 🧪 Advanced Techniques
- Used **GridSearchCV** for hyperparameter optimization.
- Applied **K-Fold Cross-Validation** for robust evaluation.

---

### 🏁 Conclusion

This notebook delivers a complete machine learning workflow by comparing classic and ensemble classifiers with neural networks. Models like **XGBoost**, **CatBoost**, and **MLP** showed strong performance, assessed through comprehensive metrics such as ROC curves and confusion matrices.
