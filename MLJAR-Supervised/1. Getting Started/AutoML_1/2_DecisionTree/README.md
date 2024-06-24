# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

11.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.37031  |  nan        |
| auc       | 0.849951 |  nan        |
| f1        | 0.619423 |    0.298178 |
| accuracy  | 0.838657 |    0.426402 |
| precision | 0.991736 |    0.984436 |
| recall    | 0.999325 |    0        |
| mcc       | 0.520013 |    0.298178 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.37031  |  nan        |
| auc       | 0.849951 |  nan        |
| f1        | 0.589754 |    0.426402 |
| accuracy  | 0.838657 |    0.426402 |
| precision | 0.770403 |    0.426402 |
| recall    | 0.477733 |    0.426402 |
| mcc       | 0.518069 |    0.426402 |


## Confusion matrix (at threshold=0.426402)
|                  |   Predicted as <=50K |   Predicted as >50K |
|:-----------------|---------------------:|--------------------:|
| Labeled as <=50K |                 4412 |                 211 |
| Labeled as >50K  |                  774 |                 708 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
