# credit_risk_analysis
------------------------
## Overview

In this project we want to take a look at how all the factors in our loan_stats csv help predict whether someone is low or high risk status. One method that data scientists use for this type of issue is creating a model and then evaluate and train the models that they create. In this specific project we are using imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. In the first couple of models I oversampled the data using randomoversampler and smote algorithms and undersample the data with the clustercentroid algorithm. In the remaining models I used a combination approach to over and undersample the data using smoteenn. Finally, I compared two machine learning models that minimize bias, balancedrandomforestclassifier and easyensembleclassifier.

-----------------------------

Accuracy score: 86.2%

Precision: 2%

High-Risk Recall: 64%

<img width="1440" alt="Screen Shot 2022-03-24 at 10 55 53 PM" src="https://user-images.githubusercontent.com/91028094/160046683-d8531696-8074-4f5f-a999-0cef230f8172.png">

<img width="1440" alt="Screen Shot 2022-03-24 at 10 56 43 PM" src="https://user-images.githubusercontent.com/91028094/160046705-92c18e4a-0257-4d77-a1bc-43b3c36d9905.png">

-------------------------------


Accuracy score: 83.4%

Precision: 2%

High-Risk Recall: 81%


<img width="1440" alt="Screen Shot 2022-03-24 at 10 57 29 PM" src="https://user-images.githubusercontent.com/91028094/160046715-91f4741f-6635-4e06-9069-163507ddd296.png">

---------------------------

Accuracy Score: 66.8%

Precision: 1%

High-Risk Recall: 63%

<img width="1440" alt="Screen Shot 2022-03-24 at 11 23 07 PM" src="https://user-images.githubusercontent.com/91028094/160048074-7783abec-13fb-437a-b2cc-9b3d7d5f180a.png">

------------------

Accuracy Score: 65.7

Precision: 1%

High-Risk Recall: 62%


<img width="1440" alt="Screen Shot 2022-03-24 at 11 07 28 PM" src="https://user-images.githubusercontent.com/91028094/160046767-918dde8b-84f4-454f-9314-d8d6fddce089.png">

----------------------

Accuracy : 43.5%

Precision : 1%

High-Risk Recall : 59%


<img width="1440" alt="Screen Shot 2022-03-24 at 11 07 36 PM" src="https://user-images.githubusercontent.com/91028094/160046791-cd6858d9-2085-4a5a-be59-9112868d7d04.png">

----------------------------

Accuracy : 53.9%

Precision : 1%

High-Risk Recall : 71%



<img width="1440" alt="Screen Shot 2022-03-24 at 11 07 42 PM" src="https://user-images.githubusercontent.com/91028094/160046802-1906c6a8-0929-4141-81e1-5902614c016f.png">

