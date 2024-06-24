# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 3_Default_Xgboost |        1 |

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.279008 | nan           |
| auc       | 0.92745  | nan           |
| f1        | 0.735304 |   0.397239    |
| accuracy  | 0.876167 |   0.555797    |
| precision | 1        |   0.987209    |
| recall    | 1        |   3.84281e-05 |
| mcc       | 0.648831 |   0.397239    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.279008 |  nan        |
| auc       | 0.92745  |  nan        |
| f1        | 0.70743  |    0.555797 |
| accuracy  | 0.876167 |    0.555797 |
| precision | 0.829401 |    0.555797 |
| recall    | 0.616734 |    0.555797 |
| mcc       | 0.642175 |    0.555797 |


## Confusion matrix (at threshold=0.555797)
|                  |   Predicted as <=50K |   Predicted as >50K |
|:-----------------|---------------------:|--------------------:|
| Labeled as <=50K |                 4435 |                 188 |
| Labeled as >50K  |                  568 |                 914 |

## Learning curves
![Learning curves](learning_curves.png)
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
