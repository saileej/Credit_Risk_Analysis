# Credit_Risk_Analysis

OVERVIEW

The purpose of this analysis was to create a reliable and accurate method with which to identify good candidates for loans.  Six ML models were created to predict which candidates are likely pay back their loans, and which candidates may default.

RESULTS

Overall, six different ML models were used to predict the likelihood of paying back credit (naive random oversampling, SMOTE oversampling, undersampling, combination sampling, balanced random forest classifier, and easy ensemble AdaBoost classifier).

The naive random oversampling method had a roughly 64% accuracy and 62% sensitivity:

![image](https://user-images.githubusercontent.com/99574730/176082333-65f26fc8-b67b-4dfc-8692-dd967f8d55f6.png)

![image](https://user-images.githubusercontent.com/99574730/176084939-180a726c-07d9-403f-af06-981795b5562d.png)


The SMOTE oversampling method had a similar accuracy rate of 63% and sensitivity of 62%:

![image](https://user-images.githubusercontent.com/99574730/176082613-7a43f567-7830-491d-b964-cfdd17893d17.png)

![image](https://user-images.githubusercontent.com/99574730/176085052-b93fe966-8cb0-4553-91c8-6c02742ed0f3.png)


Next, the undersampling model had a significantly lower accuracy rate of 53%, though a comparable sensitivity rate of 61%:

![image](https://user-images.githubusercontent.com/99574730/176082665-23cb615a-b128-4634-a7f3-d1e6644ab3ec.png)

![image](https://user-images.githubusercontent.com/99574730/176085178-4ccfbad6-3be4-4a0d-a3d0-a3a478a232b9.png)


Combination sampling resulted in a 62% accuracy rate and a higher sensitivty rate of 71%:

![image](https://user-images.githubusercontent.com/99574730/176082760-b68c1d64-8c64-40a2-8ff3-56ac4dea152e.png)

![image](https://user-images.githubusercontent.com/99574730/176085233-182b34ba-e3e1-4eb6-8ed4-665f9f93b8c5.png)


The balanced random forest classifier model had a significantly higher accuracy rate of 79%.  In addition, the model had an overall sensitivity rate of 70%.  The high-risk sensitivity was 87%, compared with a low-risk rate of 70%.

![image](https://user-images.githubusercontent.com/99574730/176083504-a5e48819-3964-4c28-9441-ef89a61fd26c.png)

![image](https://user-images.githubusercontent.com/99574730/176085338-b3007f68-a284-4d76-bbfe-705659be7f60.png)


Lastly, the highest accuracy rate was seen from the AdaBoost classifier, as well as the highest sensitivity rates.  In addition, the model shows a roughly similar sensitivity for both high-risk and low-risk clients (94% and 92%, respectively):

![image](https://user-images.githubusercontent.com/99574730/176083575-324ab052-bce9-4c65-96e1-245ef485708e.png)

![image](https://user-images.githubusercontent.com/99574730/176085489-4c6bf800-c224-487b-a20c-5c6f37799121.png)


ANALYSIS
Based on the accuracy and precision rates of the six ML models used, the last model used (AdaBoost classifier) offers the best insight into credit risk.  With a balanced accuracy score of 93% and a 92% overall sensitivity rate, this model was significantly more accurate and precise than the other 5.  Of the resampling methods (naive random oversampling, SMOTE oversampling, undersampling, and combination sampling), no single model had a significantly different accuracy rate.
