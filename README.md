# Heart Disease Prediction

A machine learning classification project that predicts the
presence of heart disease using patient health-related features.

## Workflow

- Explored the dataset using basic EDA.
- Removed duplicate records.
- Split data into training and testing sets.
- Compared six classification algorithms.

## Conclusion

Multiple classification algorithms were evaluated on the UCI Heart Disease dataset.

The models were compared using accuracy, precision, recall, F1-score,
ROC-AUC, and confusion matrices.

Because the primary objective was to minimize false negatives,
recall for the Disease class was given particular importance.

KNN provided a strong balance between disease recall and overall
classification performance on the held-out test set.

A decision threshold of 0.40 was additionally evaluated to investigate
the trade-off between false negatives and false positives.

The final model was saved as `heart_disease_knn.pkl`.

## Final Model

AdaBoost Classifier

Test Accuracy: 82%
Test AUC: 85.61%

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
