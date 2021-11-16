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
         
# 10. Mutual Fund Analysis:

![download](https://user-images.githubusercontent.com/77626222/141685539-2a8f55b3-9a2c-4e3e-87c3-1516bd518bef.jpg)

Aim:
         To Analyse various parameters related to the Hybrid Mutual fund dataset and find distinction between good and bad schemes

Conclusion:   
         upto 53.3% of the schemes are bad!
         
# 11. New York Stock Exchange Predictions:


![giphy-downsized-large](https://user-images.githubusercontent.com/77626222/141719435-54750e06-c7c4-4b41-88fc-36893c45c9a1.gif)

         # Result:
         plot of the graph of stock prices with time:

![download](https://user-images.githubusercontent.com/77626222/141719232-a4d60ba1-2145-4814-9a57-e81fedf1a30a.png)

(Red - Predicted Stock Prices  ,  Blue - Actual Stock Prices)

# 12. Kyphosis Disease Classification:

![images (1)](https://user-images.githubusercontent.com/77626222/141730775-d284668d-2dec-4c07-a3df-c15542874e73.jpg)

About:

   Kyphosis is an abnormally excessive convex curvature of the spine. The kyphosis data frame has 81 rows and 4 columns. representing data on children who have had corrective spinal surgery. 
         
INPUTS:

         Age: in months
         Number: the number of vertebrae involved
         Start: the number of the first (topmost) vertebra operated on.

OUTPUTS:

   Kyphosis: a factor with levels absent present indicating if a kyphosis (a type of deformation) was present after the operation.
         
1. DecisionTreeClassifier:    
     
        Confusion matrix:
 ![download](https://user-images.githubusercontent.com/77626222/141731949-a8c26dae-faf1-4932-abd9-6552632ab1ad.png)

2. RandomForestClassifier:

        Confusion matrix:
![download (2)](https://user-images.githubusercontent.com/77626222/141732013-c8df4554-6527-4203-b798-c9287b0963b3.png)

# 13. Mortality Prediction ICU:

![images](https://user-images.githubusercontent.com/77626222/141788463-1a4cc4e6-512c-4de3-8f52-7f665c26c3de.png)

ANN Sequential Model:

![download](https://user-images.githubusercontent.com/77626222/141788871-0fcf0ae7-5b52-4de4-b8ea-72f7bdba3c0d.png)
         
         accuracy_score = 0.86875
Summary:

         The above model has a loss of 0.27 and an accuracy of about 86%. This is the maximum accuracy it can reach with the given size of data.
         This model can be successfully used for predicting mortality in ICUs but then one should keep in mind that these values are just predicted values and the predictions            can be wrong.         

# 14. Suicide rate trend analysis:

![images](https://user-images.githubusercontent.com/77626222/141795283-b649654e-8e4a-43a7-9fb9-a57327987e97.jpg)

Machine Learning Model:

The following algorithms will be tested on the given dataset and the one with the best performance would be declared suitable:
        
         Random Forest RMSE    : 47.09774965539696
         Decesion Tree RMSE    : 61.62399259197895
         Linear Regression RMSE: 66.7226486008311
         SVR RMSE              : 88.8432701239121
         
# 15 . Customers Clustering Analysis:

Kmeans Algorithm:

![fe43cd8457302ccbc7023c0984c2e42b](https://user-images.githubusercontent.com/77626222/141915030-ac26e589-1c04-4547-a735-9e8cda7fa1f0.jpg)

   Clustering Analysis gives us a very clear insight about the different segments of the customers in the Mall. There are clearly Five segments of Customers namely Miser, General, Target, Spendthrift, Careful based on their Annual Income and Spending Score which are reportedly the best factors/attributes to determine the segments of a customer in a Mall.
      
   According to my own intuition by looking at the clustering plot between the age of the customers and their corresponding spending scores, I have aggregated them into 4 different categories namely Usual Customers, Priority Customers, Senior Citizen Target Customers, Young Target Customers. Then after getting the results we can accordingly make different marketing strategies and policies to optimize the spending scores of the customer in the Mall.

# 16. Movie Recommendation System:

![download (1)](https://user-images.githubusercontent.com/77626222/141932028-aed79b7b-567a-4519-9dac-7b246bf7dd36.jpg)

Dataset: movie_metadata

Problem Statement:

         Perform analysis and Basic Recommendations based on Similar Genres and Movies which Users prefer.

Some of the Key Points on which we will be focusing include:

         Profitability of Movies
         Language based Gross Analysis
         Comparison of Gross and Profit for Different Genres,
         Recommendation systems based on Actors, Movies, Genres.
         
Calculating Profit of a Movie:
         
Budget: It is an amount which Producers Spend to Produce a Movie which Includes the Production, casting, and Advertisements cost.
Gross: It is an amount which Producers earn by releasing their movies in theaters, selling satellite rights to TV, OTT Platforms such as Prime, Hulu, Disney+Hotstar, Netflix etc.
         
         Profit: Gross - Budget
         
Calculating Social Media Popularity:
Important Factors to determine the Social Media Popularity includes:

         Number of People who voted for the Movie.
         Number of People who Reviewed the Movie.
         Number of Facebook Likes on the Movie Page.
         
Using these Metrics, we have come up with a Formula to calculate the Social Media Popularity of these Movies.

         (No. of People Reviewed for Movie/No. Of People Voted for Movie)*No. Of Facebook Likes

Project Link: https://github.com/Harishpatil0172/Data_Science_Project/tree/main/Movie%20Recommendation%20Engine

# 17. Analyzing the Growth of Indian Startups:

![for-magicpin-startup-story_thinkstockphotos-516796850](https://user-images.githubusercontent.com/77626222/141989851-99998a02-6b8f-4cad-97ec-90008b18a74b.gif)

Dataset- startup_funding.csv

On Average indian startups got funding of :  132706955.99

analyse:

         1. How Does the Funding Ecosystem changes with respect to Time?
         2. What is the General Amount that Startups get in India?
         3. Which Kind of Industries are more preferred for Startups?
         4. Does Location also play a role, In determining the Growth of a Startup?
         5. Who plays the main role in Indian Startups Ecosystem?
         6. What are the different Types of Funding for Startups?
