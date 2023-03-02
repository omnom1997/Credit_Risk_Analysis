# Credit Risk Analysis

Title and multiple sections
Each section has a heading and subheading
Links to images are working and code is formatted and displayed correctly 

## Overivew
### Purpose
For this analysis, we were tasked with evaluating credit card risk using machine learning. We employed several different techniques to train and evaluate models with unbalanced classes. Our first two models were created with oversampled data using the RandomOverSampler and SMOTE algorithms. We then undersampled our next model using the ClusterCentroids. We next used a combinatorial approach of over and undersampling using the SMOTEENN algorithm. Our last two modles reduced bias, and they were BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results
### Oversampling
#### 1. Naive Random Oversampling

- Accuracy: 64.4%

![image](https://user-images.githubusercontent.com/114427019/222320059-2c040750-45a6-416c-86a6-3a3657080a9e.png)

- Precision: 99.7%
- Recall: 59.5%
- Analysis table:

![image](https://user-images.githubusercontent.com/114427019/222318117-762c992e-c56e-4aaf-99c1-4f4433f31d8c.png)

#### 2. SMOTE Oversampling

- Accuracy: 66.3%

![image](https://user-images.githubusercontent.com/114427019/222320276-6e3c54e0-ba5e-4cdd-8866-2e3a27eeb0cc.png)

- Precision: 99.7%
- Recall: 69.2%
- Analysis table:

![image](https://user-images.githubusercontent.com/114427019/222318223-05cc5c0d-a9e7-4a1e-8757-f9e35f014184.png)

### Undersampling
#### 1. Cluster Centroids
- Accuracy: 54.5%

![image](https://user-images.githubusercontent.com/114427019/222320425-3b398090-5805-4c2d-a3d2-31959a5f17af.png)

- Precision: 99.5%
- Recall: 39.6%
- Analysis table:

![image](https://user-images.githubusercontent.com/114427019/222318348-7465d502-59c3-4cc8-9e7a-99b3dfff2bf4.png)

### SMOTEENN
- Accuracy: 64.5%

![image](https://user-images.githubusercontent.com/114427019/222321308-1c8344e5-490c-4689-9749-1a19c63b1423.png)

- Precision: 99.7%
- Recall: 56.7%
- Analysis table:

![image](https://user-images.githubusercontent.com/114427019/222321508-79b59119-4856-439a-84a3-599716644152.png)

### Ensemble Classifiers to Predict Credit Risk
#### 1. Balanced Random Forest Classifier
- Accuracy: 68.3%

![image](https://user-images.githubusercontent.com/114427019/222320603-48ba8f53-62f3-47a4-8b6f-84d4853be691.png)

- Precision: 99.6%
- Recall: 99.9%
- Analysis table:

![image](https://user-images.githubusercontent.com/114427019/222318441-07b815aa-a75a-4e22-a3e9-a2046c0b1fae.png)

#### 2. Easy Ensemble Classifier
- Accuracy: 93.2%

![image](https://user-images.githubusercontent.com/114427019/222320771-8d586e94-68dd-4c7b-bb52-7d7c35e259f1.png)

- Precision: 99.9%
- Recall: 94.3%
- Analysis table:

![image](https://user-images.githubusercontent.com/114427019/222318550-835c0b02-b354-4138-86fe-096076fdc102.png)

## Summary
In summary, the model that we would recommend using is the Easy Ensemble Classifier as it has a high recall percentage as well as a high accuracy percentage. A high recall is important because we want people who are a high credit risk to be correctly flagged by our model rather than potenially have our model miss indiviuals who are a high credit risk.
