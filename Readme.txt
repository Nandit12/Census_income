Dataset from :- https://www.kaggle.com/niwech/census-income-dataset
Task :- Prediction task is to determine whether a person makes over 50K a year.
About data :- Imbalanced dataset with high proportion of people from <=50k category.
Models used :- Decision Tree classification, svm and then SMOTE with decision tree.
Evaluation :- 1) Decision Tree gives an accuracy of 82%, but this is misleading as
                 the data is imbalanced. It fails to predict people having income >50k.
                 check screenshot1.
              2) SVM gives 66% accuracy and also fails to predict people having income >50k.
                 check screenshot2.
              3) SMOTE is used which is a technique to do oversampling of data which helps in
                 increasing the proportion of minority class.
              4) Decision Tree is used on SMOTE data which gives an accuracy of 75% but gives high
                 accuracy on people having income >50k.
                 check sceenshot3.

              
