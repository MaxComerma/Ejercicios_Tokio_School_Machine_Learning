# Machine Learning — Tokio School Exercises

A collection of practical machine-learning exercises completed during a Machine Learning course at Tokio School.

The repository covers supervised and unsupervised learning, model evaluation, regularization, feature interpretation and practical applications using Python and scikit-learn.

> **Language:** Most original exercises are in Spanish. Selected exercises have been translated or rewritten in English.

## At a glance

| | |
|---|---|
| **Focus** | Applied Machine Learning |
| **Language** | Python |
| **Core tools** | pandas, NumPy, Matplotlib, scikit-learn, SHAP |
| **Supervised learning** | Linear regression, logistic regression, KNN, decision trees, random forests, SVM |
| **Unsupervised learning** | K-Means, hierarchical clustering, PCA |
| **Model evaluation** | Train/test split, cross-validation, confusion matrices, classification reports |
| **Model interpretation** | Feature importance, permutation importance, SHAP |
| **Additional topics** | Regularization, normalization, forecasting and APIs |

## Selected exercises

| Notebook | Problem | Method | Result |
|---|---|---|---|
| `English Exercises/Decision_Tree_and_Random_Forest_Exercise.ipynb` | Iris classification | Random Forest | Test accuracy **1.00** |
| `English Exercises/KNN_Exercise.ipynb` | Iris classification | KNN | Reported test accuracy **1.00**; error rate **0.0** |
| `English Exercises/Cross_Validation_Techniques.ipynb` | Model selection | Cross-validation + GridSearchCV | Reported best models reached **1.00 mean CV accuracy** and **1.00 test accuracy** in the corresponding exercises |
| `Interpretation and improvement of supervised learning models/Ejercicio_SHAP_Max_Comerma.ipynb` | Customer churn prediction | Random Forest + GridSearchCV + SHAP | Test accuracy **0.7868**; churn-class F1 **0.57** |
| `Interpretation and improvement of supervised learning models/Regresión_Lasso_y_Ridge_Max_Comerma.ipynb` | Sales prediction | Ridge vs Lasso regression | Ridge R² **0.9171**; Lasso R² **0.9179** |


## Topics

### Supervised Learning

- Linear regression
- Logistic regression
- Decision trees
- Random forests
- K-nearest neighbours
- Support Vector Machines
- Model evaluation
- Cross-validation

### Regression

- Least-squares fitting
- Cost functions
- Gradient descent
- Prediction
- Hyperparameters
- Ridge regression
- Lasso regression

### Model Interpretation

- Feature importance
- Permutation importance
- SHAP
- Model comparison

### Unsupervised Learning

- K-Means
- Hierarchical clustering
- PCA
- Semi-supervised learning

### Other

- Forecasting
- APIs
- Synthetic datasets
- Data normalization

## Limitations & next steps

This repository is a collection of course exercises rather than a single production ML pipeline.

Many datasets are small educational datasets. Reported metrics should therefore be interpreted as exercise results rather than evidence of real-world predictive performance.

