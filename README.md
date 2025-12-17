# Diabetes Classification with Machine Learning

This project applies various machine learning classification algorithms 
to the Pima Indians Diabetes Dataset in order to predict whether a patient 
has diabetes or not.

## Dataset
- Pima Indians Diabetes Dataset
- Missing values represented as 0 were handled using median imputation.

## Preprocessing
- Zero values in physiological features were treated as missing data
- Median imputation was applied using training data only
- StandardScaler was used for feature scaling

## Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- AdaBoost

## Results
Random Forest achieved the best performance with approximately **79% accuracy**, 
showing better generalization and balance between precision and recall.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Conclusion
Ensemble methods, especially Random Forest, outperformed individual classifiers 
on this dataset.

## Author
- SK
