# Folder '3 - Evaluation metrics for classification model ' 
Has the python code to Calculate evaluation metrics for a classification model using confusion matrix.

    - Sensitivity or recall, or true positive rate = correct positive classifications / real total positive = TP / TP + FN
```math
\frac{TP}{TP + FN}
```
    - Specificity or False positive rate = correct negative classifications / real total negative = TN / TN + FP
```math
\frac{TN}{TN + F}
```
    - Accuracy = correct classifications / total classifications = TP + TN / N
```math
\frac{TP + TN}{N}
```
    - Precision = correct positive classifications / total positive classifications = TP / TP + FP 
```math
\frac{TP}{TP + FP}
```
    - F-Score = 2 * (Precision * Sensitivity) / (Precision + Sensitivity)
```math
2*\frac{Precision * Sensitivity}{Precision + Sensitivity} = 2*\frac{\frac{TP}{TP + FP} * \frac{TP}{TP + FN}}{\frac{TP}{TP + FP} + \frac{TP}{TP + FN}}
```

Legend:

    TP = True positive
    FP = False positive
    TN = True negative 
    FN = False negative
    N = Total classifications
