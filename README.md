# Predictive HR Analytics


## Project Overview

This project predicts whether an employee is likely to leave the company using **Logistic Regression**. The project also explores **L1 (Lasso)** and **L2 (Ridge)** regularization techniques to improve model generalization and reduce overfitting.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

## Machine Learning Models

* Logistic Regression
* Logistic Regression (L1 Regularization)
* Logistic Regression (L2 Regularization)

## Workflow

1. Load the employee turnover dataset.
2. Split the data into training and testing sets.
3. Train a Logistic Regression model.
4. Train Logistic Regression with L1 (Lasso) Regularization.
5. Train Logistic Regression with L2 (Ridge) Regularization.
6. Evaluate the model using multiple classification metrics.

## Model Performance

| Metric    |      Value |
| --------- | ---------: |
| Accuracy  | **85.93%** |
| Precision | **87.18%** |
| Recall    | **81.60%** |
| F1 Score  | **84.30%** |

### Confusion Matrix

```
[[130  15]
 [ 23 102]]
```

### Interpretation

* The model correctly classified **130** employees who stayed.
* The model correctly identified **102** employees who left.
* **15** employees were incorrectly predicted to leave.
* **23** employees who actually left were incorrectly predicted to stay.

## Conclusion

The Logistic Regression model achieved an **Accuracy of 85.93%**, demonstrating strong predictive performance for employee turnover classification. The high precision (**87.18%**) indicates that when the model predicts an employee will leave, it is usually correct. An F1 Score of **84.30%** reflects a good balance between precision and recall. This model provides a reliable baseline for employee attrition prediction and can be further enhanced using advanced machine learning algorithms such as Random Forest, XGBoost, or Gradient Boosting.

## Libraries Required

```bash
pip install pandas numpy scikit-learn
```
