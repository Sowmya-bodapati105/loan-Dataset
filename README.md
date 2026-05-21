# loan-Dataset
# Machine Learning Hyperparameter Tuning 🚀

This repository contains implementations of different **Machine Learning Algorithms** with **Hyperparameter Tuning** using **GridSearchCV** and **Pipeline** concepts in Scikit-learn.

## 📂 Included Algorithms

* K-Nearest Neighbors (KNN)
* Logistic Regression
* Support Vector Classifier (SVC)
* Decision Tree Classifier
* Naive Bayes

---

## 📘 Topics Covered

* Data Preprocessing
* Handling Missing Values
* Feature Scaling
* Encoding Categorical Features
* Pipeline Implementation
* Hyperparameter Tuning
* GridSearchCV
* Model Evaluation

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## 📁 Files in Repository

| File Name                           | Description                         |
| ----------------------------------- | ----------------------------------- |
| `KNN_hyper_parameter_1(1).ipynb`    | KNN with Hyperparameter Tuning      |
| `logistic_hyper_parameter.ipynb`    | Logistic Regression Tuning          |
| `svc_hyper_parameter.ipynb`         | Support Vector Classifier Tuning    |
| `decision_hyper_parameter.ipynb`    | Decision Tree Hyperparameter Tuning |
| `naive_bayes_hyper_parameter.ipynb` | Naive Bayes Implementation          |

---

## ⚡ Hyperparameter Tuning

Example parameters used:

### KNN

* `n_neighbors`
* `weights`
* `metric`

### Logistic Regression

* `C`
* `penalty`
* `solver`

### SVC

* `C`
* `kernel`
* `gamma`

### Decision Tree

* `max_depth`
* `min_samples_split`
* `criterion`

### Naive Bayes

* `var_smoothing`

---

## 🔄 Pipeline Workflow

```python
Pipeline([
    ('preprocessor', preprocessor),
    ('model', classifier)
])
```

---

## 📊 Model Evaluation Metrics

* Accuracy Score
* Classification Report
* Confusion Matrix
* Cross Validation

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone <your-github-repo-link>
```

2. Install required libraries

```bash
pip install pandas numpy scikit-learn matplotlib
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run the notebooks

---

## 🎯 Learning Outcome

By completing these notebooks, you will understand:

* End-to-End Machine Learning Workflow
* Real-world Pipeline Usage
* Hyperparameter Optimization
* Model Selection Techniques
* Best Practices in Scikit-learn

---

## ⭐ Future Improvements

* Add RandomizedSearchCV
* Add Ensemble Algorithms
* Add XGBoost & Random Forest
* Deploy Models using Flask/Streamlit

---

## 👩‍💻 Author

**Venkata Sowmya PadmaSri**

Machine Learning & Data Science Learner 🌱
