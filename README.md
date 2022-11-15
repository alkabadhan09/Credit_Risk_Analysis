# Credit_Risk_Analysis

## Overview

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results

### Random Oversampler

* Balanced Accuracy Score: 65%
* Precision Score: 99%
* Recall Score: 69%

![creditrisk1](https://user-images.githubusercontent.com/107225715/201804853-f740e65a-a260-4392-8512-2296989a0b30.png)
![creditrisk2](https://user-images.githubusercontent.com/107225715/201804865-2bfea01b-aa03-448e-9acf-0d69d9f850ce.png)

### SMOTE Oversampling

* Balanced Accuracy Score: 65%
* Precision Score: 99%
* Recall Score: 66%

![creditrisk3](https://user-images.githubusercontent.com/107225715/201804875-bdbe7860-69ad-4d47-b523-0c71d8175420.png)
![creditrisk4](https://user-images.githubusercontent.com/107225715/201804883-bdf3987c-c1e6-4dd3-a5ef-57b1b5a008b5.png)

### Oversampling

* Balanced Accuracy Score: 65%
* Precision Score: 99%
* Recall Score: 69%

![creditrisk5](https://user-images.githubusercontent.com/107225715/201804890-b311dd38-188b-4aee-baa5-2ef84c18d31d.png)

### Combination (Over and Under) Sampling

* Balanced Accuracy Score: 65%
* Precision Score: 99%
* Recall Score: 58%

![creditrisk6](https://user-images.githubusercontent.com/107225715/201804900-d5c3d682-e83c-4ebc-89a6-5a44c834d202.png)

### Balanced Random Forest Classifier

* Balanced Accuracy Score: 77%
* Precision Score: 99%
* Recall Score: 88%

![creditrisk7](https://user-images.githubusercontent.com/107225715/201804919-21177b13-b2ff-44a2-bab9-1865a7d92962.png)

### Easy Ensemble AdaBoost Classifier

* Balanced Accuracy Score: 92%
* Precision Score: 99%
* Recall Score: 94%

![creditrisk8](https://user-images.githubusercontent.com/107225715/201804937-b8c1c5bc-b9fc-4e87-980a-f7f4f1e7eaa5.png)

## Summary

Different resampling methids such as oversampling, undersampling and a combination were used and the best one was Ensamble Classifier as it produced the best Balanced accuracy score, 92%, Precision score, 99%, and Recall score which is 94%. Therefore, my recommendation is to use Easy Ensemble AdaBoost Classifier based on the listed results. 
