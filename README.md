# Data_Science_Project
# 1.  Predict Employee Attrition:

![download](https://user-images.githubusercontent.com/77626222/141610310-ff7898a5-2fbd-42f6-9e47-ee8d89d10c59.gif)

         1) Logistic regression accuracy   : 0.766
         2) Random Forest Accuracy         : 0.965
         3) Support vector machine accuracy: 0.891
         4) XGBoost accuracy               : 0.957
         
         cross validation average accuracy for Random Forest Classifier: 0.961
         cross validation average accuracy for SVM Classifier          : 0.891
         cross validation average accuracy for XGBoost Classifier      : 0.956
  
# 2. Car Price Prediction:

![download](https://user-images.githubusercontent.com/77626222/141260960-7f2708c9-7ac6-4223-bd9c-83661e6e92ab.png)

  i) Using Random Forest Regressor:
  
      MAE : 0.89
      MSE : 4.02
      RMSE: 2.00
      
  ii) Using XGBoost Regressor:
  
      MAE : 0.74
      MSE : 2.56
      RMSE: 1.60
      
  iii) Using Catboost Regresssor:
  
      MAE : 1.01
      MSE : 3.93
      RMSE: 1.98
      
# 3. Bigmart_Sales_Prediction:
![Bigmart-Sales-Prediction-Project-using-Machine-Learning-code-free-download-B Tech-Projects-1](https://user-images.githubusercontent.com/77626222/141477629-296f4e96-fdae-4fff-96dc-322b8ea948bb.png)

           1) Linear Regression:
                CV Score: 0.28
           2) Ridge Regression:
                CV Score: 0.42
           3) Lasso Regression:
                CV Score: 0.75
           4) DecisionTreeRegressor:
                CV Score: 0.55
           5) RandomForestRegressor:
                CV Score: 0.29
           6) ExtraTreesRegressor:
                CV Score: 0.32
           7) LGBMRegressor:
                CV Score: 0.28

# 4. Loan Approval Prediction:
![download](https://user-images.githubusercontent.com/77626222/141475982-ade3fbd3-9c3d-4cb5-bbbe-42ae58a3992e.jpg)

         1) LogisticRegression:
                Accuracy = 78.37
         2) DecisionTreeClassifier:
                Accuracy = 70.81
         3) RandomForestClassifier:
                Accuracy = 78.91
         4) ExtraTreesClassifier:
                Accuracy = 72.43
         5) XGBClassifier:
                Accuracy = 77.83
         6) LGBMClassifier:
                Accuracy = 76.75
         7) RandomizedSearchCV:
                Accuracy = 80.94
               
# 5. Stroke prediction problem:
![brain](https://user-images.githubusercontent.com/77626222/141477290-35bc4a9e-dc9f-43ba-99f4-ffce6895ad9c.png)

    Naive_Bayes score   = 0.97
    Decision tree score = 0.95
    Random Forest score = 0.98
    MLP score           = 0.97
         
# 6. Apparent Temperature Prediction:

![giphy](https://user-images.githubusercontent.com/77626222/141610494-df4de08b-fbe8-4530-a9ca-084cc356b9ad.gif)


         1) LinearRegression accuracy = 0.992
         2) XGBRegressor:
            Mean Absolute Error    :  0.116
            Mean Squared Error     :  0.031
            Root Mean Squared Error:  0.176
         3) LGBMRegressor:
            Mean Absolute Error    :  0.126
            Mean Squared Error     :  0.052
            Root Mean Squared Error:  0.229
         4) CatBoostRegressor:
            Mean Absolute Error    :  0.144
            Mean Squared Error     :  0.054
            Root Mean Squared Error:  0.233
         5) StackingRegressor:
            Mean Absolute Error    :  0.501
            Mean Squared Error     :  0.368
            Root Mean Squared Error:  0.607
    
# 7. Live Sketch Project:

![1_HY4pzxg9ClQmg5Ao5V_4DA](https://user-images.githubusercontent.com/77626222/141650704-90ca22e2-a7aa-4e54-83ac-b8b02993c153.png)


         First convert the image into grayscale and then blur the background.
         lastly, add the black and white foreground to the blurred background.
         TO seperate the background we invert image and then we'll blur it,
         and our final output will be the frame recorded by the webcam.
         
   Tools Used:
   
            1. Anaconda prompt
            2. Spyder ide
            3. Opencv Python
   
# 8. Blood Donation Analysis:

![download](https://user-images.githubusercontent.com/77626222/141669474-c3d5e792-299d-486a-a256-af030ba4d2ee.jpg)

## Aim Of Project:
         To build a model which can identify who is likely to donate blood again.
         
Models implemented:

         1. Logistic Regression:
                  accuracy_score = 0.71 
                  roc_auc_score  = 0.73
         2. Suport Vector Machine:
                  accuracy_score = 0.78 
                  roc_auc_score  = 0.84
         3. Random Forest:
                  accuracy_score = 0.75 
                  roc_auc_score  = 0.77
         4. Decision Tree:
                  accuracy_score = 0.73 
                  roc_auc_score  = 0.73
         5. MLP Classifier:
                  accuracy_score = 0.78 
                  roc_auc_score  = 0.73
                  
# 9. E-Signing of Loan Based on Financial History:

![download](https://user-images.githubusercontent.com/77626222/141684188-226076aa-286e-4196-bd84-9574c1fc96d7.png)

         
         Electronic signatures aren’t exactly a novelty. They have been around since the American Civil War, during which contracts were signed through Morse. In a modern      setting, an e-Sign refers to a unique, digitised, encrypted personal identifier. This is, in essence, different from the ‘wet’ signatures created by hand. The e-Sign is meant to complete transactions, loops, and agreements electronically.

In India, the e-Sign has been granted legal status by amendments to various laws, namely the Information Technology Act, Indian Evidence Act and the Negotiable Instruments Act. Early adopters in the financial sector have started using e-Sign to get customers to sign loan and card applications, and loan agreements.
         
   Models implemented:
     
         1. Artificial Neural Network (accuracy_score = 60.99)
         2. Random Forest Classifier  (accuracy_score = 61.84)
         3. Gradient Boosting         (accuracy_score = 58.30)
         4. Support Vector Machine    (accuracy_score = 58.87)
         5. Xg Boost                  (accuracy_score = 62.78)
   Conclusion:
   
         XgBoost Algorithm performs the best and give the accuracy of 62 %
         We see that the ANN with no feature engineering performs far better than SVM, Random Forest with feature engineering
         Though we didnt get very high accuracy but this can help the banks in knowing whether the customer is risky or not.
