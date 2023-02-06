# Credit_Risk_Analysis

## Overview
The purpose of this analysis was predict credit risk using various models which includes oversampling data using the RandomOverSampler and SMOTE algorithms, undersampling data using the ClusterCentroids algorithm. Then, using a combination approach of both over and undersampling data using the SMOTEENN algorithm. We also used two new machine learning models that reduces bias, called the BalancedRandomForestClassifier and the EasyEnsembleClassifier, to predict credit risk.


## Results
1. RandomOverSampler; - balanced accuracy scores: 0.65
                      - precision: high risk(0): 0.01 and low risk(1): 1.0
                      - recall scores: high risk(0): 0.72 and low risk(1): 0.59
  ![Screenshot 2023-02-06 at 12 15 10 AM](https://user-images.githubusercontent.com/109382758/216889659-0a7c4b71-5dfd-4c85-8a8e-42ca8f8dc611.png)

                     
2. SMOTE Oversampling; - balanced accuracy scores: 0.66
                       - precision: high risk(0): 0.01 and low risk(1): 1.0
                       - recall scores: high risk(0): 0.63 and low risk(1): 0.69
 ![Screenshot 2023-02-06 at 12 15 24 AM](https://user-images.githubusercontent.com/109382758/216889610-b7f56ea5-9a53-4522-9fc7-5b42bc33a465.png)
                                       
3. ClusterCentroids algorithm; - balanced accuracy scores: 0.54
                               - precision: high risk(0): 0.01 and low risk(1): 1.0
                               - recall scores: high risk(0): 0.69 and low risk(1): 0.40
 ![Screenshot 2023-02-06 at 12 15 36 AM](https://user-images.githubusercontent.com/109382758/216889549-acafec1d-b6e5-42f3-995f-d36326f672c6.png)

                     
4. SMOTEENN algorithm; - balanced accuracy scores: 0.65
                       - precision: high risk(0): 0.01 and low risk(1): 1.0
                       - recall scores: high risk(0): 0.72 and low risk(1): 0.57
  ![Screenshot 2023-02-06 at 12 15 50 AM](https://user-images.githubusercontent.com/109382758/216889520-74799e70-41f1-4ee1-ac17-d07694be679f.png)

                    
5. BalancedRandomForestClassifier; - balanced accuracy scores: 0.79
                                   - precision: high risk(0): 0.03 and low risk(1): 1.0
                                   - recall scores: high risk(0): 0.70 and low risk(1):0.87
  ![Screenshot 2023-02-06 at 12 16 07 AM](https://user-images.githubusercontent.com/109382758/216889473-87b0faea-2922-4fd7-b2f1-5cddd8880682.png)

                      
6. EasyEnsembleClassifier; - balanced accuracy scores: 0.79
                           - precision: high risk(0): 0.03 and low risk(1): 1.0
                           - recall scores: high risk(0): 0.70 and low risk(1): 0.87
![Screenshot 2023-02-06 at 12 16 18 AM](https://user-images.githubusercontent.com/109382758/216889430-9b563a49-64cc-488a-8781-ec13aeeabc2b.png)



## Summary

The summary of the results;
1. The accuracy score of the RandomOverSampler which shows the pecentage of correct prediction is 65%. The high risk precision here is very low at 0.01 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 72% and a low risk of 59%.
2. The accuracy score of the SMOTE Oversampling which shows the pecentage of correct prediction is 66%. The high risk precision here is very low at 0.01 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 63% and a low risk of 69%.
3. The accuracy score of the ClusterCentroids algorithm which shows the pecentage of correct prediction is 54%. The high risk precision here is very low at 0.01 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 69% and a low risk of 40%.
4. The accuracy score of the SMOTEENN algorithm which shows the pecentage of correct prediction is 65%. The high risk precision here is very low at 0.01 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 72% and a low risk of 57%.
5. The accuracy score of the BalancedRandomForestClassifier which shows the pecentage of correct prediction is 79%. The high risk precision here is very low at 0.03 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 70% and a low risk of 87%.
6. Lastly, the accuracy score of the EasyEnsembleClassifier which shows the pecentage of correct prediction is 79%. The high risk precision here is very low at 0.03 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 70% and a low risk of 87%.

Therefore, I would personally recommend the ensemble models because the model types used showed the highest accuracy model which is very close to the highest accuracy a model cam predict
