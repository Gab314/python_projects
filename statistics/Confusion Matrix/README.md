# Confusion Matrix

> In Predictive analysis, the confusion matrix is used to compare the predicted classification vs the actual classification.

## Index
+ Binary
    + Matrix
    + Errors
    + Metrics
+ Categorical
    + Metrics

## Binary

### Matrix
Here we take a look at the simplest form of the matrix. a `2x2` with 2 classes, usually `True` or `False`.

| Actual \ Predicted    | Positive          |           Negative |
| :---:                 | :---:             | :---:              |
| Positive              | `True` Positive   | **False** Negative   |
| Negative              | **False** Positive  | `True` Negative    |

Dissecting it.
True Positive : `True` Correct Prediction, with `Positive` Result.
True Negative : `True` Correct Prediction, with `Negative` Result.

### Errors

`Type I`  Error : False Positive.
`Type II` Error : False Negative.