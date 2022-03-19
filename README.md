# Detection-of-Heart-Disease-using-Classification-Algorithm
Detection of Heart Disease using Classification Algorithm
data description
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 1025 entries, 0 to 1024
Data columns (total 14 columns):
 #   Column    Non-Null Count  Dtype  
---  ------    --------------  -----  
 0   age       1025 non-null   int64  
 1   sex       1025 non-null   int64  
 2   cp        1025 non-null   int64  
 3   trestbps  1025 non-null   int64  
 4   chol      1025 non-null   int64  
 5   fbs       1025 non-null   int64  
 6   restecg   1025 non-null   int64  
 7   thalach   1025 non-null   int64  
 8   exang     1025 non-null   int64  
 9   oldpeak   1025 non-null   float64
 10  slope     1025 non-null   int64  
 11  ca        1025 non-null   int64  
 12  thal      1025 non-null   int64  
 13  target    1025 non-null   int64  
dtypes: float64(1), int64(13)
memory usage: 112.2 KB
--------------------------------------
classification report for Logistic Regression: 
              precision    recall  f1-score   support

           0       0.83      1.00      0.91        20
           1       1.00      0.88      0.93        32

    accuracy                           0.92        52
   macro avg       0.92      0.94      0.92        52
weighted avg       0.94      0.92      0.92        52

 classification report for Decision Tree: 
              precision    recall  f1-score   support

           0       0.80      1.00      0.89        20
           1       1.00      0.84      0.92        32

    accuracy                           0.90        52
   macro avg       0.90      0.92      0.90        52
weighted avg       0.92      0.90      0.91        52

 classification report for Random Forest: 
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        20
           1       1.00      1.00      1.00        32

    accuracy                           1.00        52
   macro avg       1.00      1.00      1.00        52
weighted avg       1.00      1.00      1.00        52

 classification report for KNN: 
              precision    recall  f1-score   support

           0       0.67      0.90      0.77        20
           1       0.92      0.72      0.81        32

    accuracy                           0.79        52
   macro avg       0.79      0.81      0.79        52
weighted avg       0.82      0.79      0.79        52

 classification report for MLP: 
              precision    recall  f1-score   support

           0       0.61      1.00      0.75        20
           1       1.00      0.59      0.75        32

    accuracy                           0.75        52
   macro avg       0.80      0.80      0.75        52
weighted avg       0.85      0.75      0.75        52

-----------------------------------------------------
accuracy model

Accuracy for Logistic Regression Model: 
0.9230769230769231

Accuracy for Decision Tree Model: 
0.9038461538461539

Accuracy for MLP Model: 
0.75

Accuracy for KNN Model: 
0.7884615384615384

Accuracy for Random Forest Model: 
1.0
