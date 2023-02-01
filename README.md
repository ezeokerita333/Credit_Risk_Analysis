# Credit_Risk_Analysis

## Overview
The purpose of this analysis was predict credit risk using various models which includes oversampling data using the RandomOverSampler and SMOTE algorithms, undersampling data using the ClusterCentroids algorithm. Then, using a combination approach of both over and undersampling data using the SMOTEENN algorithm. We also used two new machine learning models that reduces bias, called the BalancedRandomForestClassifier and the EasyEnsembleClassifier, to predict credit risk.


## Results
1. RandomOverSampler; - balanced accuracy scores: 0.65
                      - precision: high risk(0): 0.01 and low risk(1): 1.0
                      - recall scores: high risk(0): 0.72 and low risk(1): 0.59
  ![Screenshot 2023-01-30 at 6 27 27 AM](https://user-images.githubusercontent.com/109382758/215766401-6c239f0d-b5fa-4d87-ae3a-b30ec9e8c9cd.png)
                     
2. SMOTE Oversampling; - balanced accuracy scores: 0.65
                       - precision: high risk(0): 0.01 and low risk(1): 1.0
                       - recall scores: high risk(0): 0.63 and low risk(1): 0.69
 ![Screenshot 2023-01-30 at 6 27 59 AM](https://user-images.githubusercontent.com/109382758/215766743-d5c583d1-1baa-431b-84a3-d111c5a66493.png)                                        
3. ClusterCentroids algorithm; - balanced accuracy scores: 0.66
                               - precision: high risk(0): 0.01 and low risk(1): 1.0
                               - recall scores: high risk(0): 0.63 and low risk(1): 0.69
 ![Screenshot 2023-01-30 at 6 28 28 AM](https://user-images.githubusercontent.com/109382758/215766949-4efa00ac-4242-4c22-8317-e2cdcf339023.png)
                     
4. SMOTEENN algorithm; - balanced accuracy scores: 0.66
                       - precision: high risk(0): 0.01 and low risk(1): 1.0
                       - recall scores: high risk(0): 0.72 and low risk(1): 0.57
  ![Screenshot 2023-01-30 at 6 28 53 AM](https://user-images.githubusercontent.com/109382758/215766976-98d5ebbe-863a-49c4-801c-299ac472300c.png)
                    
5. BalancedRandomForestClassifier; - balanced accuracy scores: 0.79
                                   - precision: high risk(0): 0.03 and low risk(1): 1.0
                                   - recall scores: high risk(0): 0.70 and low risk(1):0.87
  ![Screenshot 2023-01-31 at 8 02 40 AM](https://user-images.githubusercontent.com/109382758/215767207-1c8cc6fd-4e55-4285-83bd-3a6da4a81229.png)
                      
6. EasyEnsembleClassifier; - balanced accuracy scores: 0.79
                           - precision: high risk(0): 0.03 and low risk(1): 1.0
                           - recall scores: high risk(0): 0.70 and low risk(1): 0.87
![Screenshot 2023-01-31 at 8 02 20 AM](https://user-images.githubusercontent.com/109382758/215767229-9ea900fa-0fff-4598-9485-55bc9aea696c.png)


## Summary

The summary of the results;
1. The accuracy score of the RandomOverSampler which shows the pecentage of correct prediction is 65%. The high risk precision here is very low at 0.01 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 72% and a low risk of 59%.
2. The accuracy score of the SMOTE Oversampling which shows the pecentage of correct prediction is 65%. The high risk precision here is very low at 0.01 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 63% and a low risk of 69%.
3. The accuracy score of the ClusterCentroids algorithm which shows the pecentage of correct prediction is 66%. The high risk precision here is very low at 0.01 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 63% and a low risk of 69%.
4. The accuracy score of the SMOTEENN algorithm which shows the pecentage of correct prediction is 66%. The high risk precision here is very low at 0.01 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 72% and a low risk of 57%.
5. The accuracy score of the BalancedRandomForestClassifier which shows the pecentage of correct prediction is 79%. The high risk precision here is very low at 0.03 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 70% and a low risk of 87%.
6. Lastly, the accuracy score of the EasyEnsembleClassifier which shows the pecentage of correct prediction is 79%. The high risk precision here is very low at 0.03 while the low risk precision is at the highest of 1.0 (showing a low measure of false positives). However, the recall score shows a high risk of 70% and a low risk of 87%.

Therefore, I would personally recommend the ensemble models because the model types used showed the highest accuracy model which is very close to the highest accuracy a model cam predict
