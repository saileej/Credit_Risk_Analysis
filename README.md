# Credit_Risk_Analysis

OVERVIEW

The purpose of this analysis was to create a reliable and accurate method with which to identify good candidates for loans.  Six ML models were created to predict which candidates are likely pay back their loans, and which candidates may default.


RESULTS

Overall, six different ML models were used to predict the likelihood of paying back credit (naive random oversampling, SMOTE oversampling, undersampling, combination sampling, balanced random forest classifier, and easy ensemble AdaBoost classifier).

The naive random oversampling method had a roughly 64% accuracy:

![image](https://user-images.githubusercontent.com/99574730/176082333-65f26fc8-b67b-4dfc-8692-dd967f8d55f6.png)


The SMOTE oversampling method had a similar accuracy rate of 63%:

![image](https://user-images.githubusercontent.com/99574730/176082613-7a43f567-7830-491d-b964-cfdd17893d17.png)


Next, the undersampling model had a significantly lower accuracy rate of 53%:

![image](https://user-images.githubusercontent.com/99574730/176082665-23cb615a-b128-4634-a7f3-d1e6644ab3ec.png)


Combination sampling resulted in a 62% accuracy rate:

![image](https://user-images.githubusercontent.com/99574730/176082760-b68c1d64-8c64-40a2-8ff3-56ac4dea152e.png)


The balanced random forest classifier model had a significantly higher accuracy rate of 79%:

![image](https://user-images.githubusercontent.com/99574730/176083504-a5e48819-3964-4c28-9441-ef89a61fd26c.png)


Lastly, the highest accuracy rate was seen from the AdaBoost classifier:

![image](https://user-images.githubusercontent.com/99574730/176083575-324ab052-bce9-4c65-96e1-245ef485708e.png)


ANALYSIS
