# Customer_Segmentation_Analysis: Project Overview

- Built a customer segmentation analysis with labeled data.
- The required dataset was available on kaggle with both train and test csv.
- Normally a customer segmentation dataset does not have labeled data, but it was provided in this one with the labeled data having unique values (A, B, C, D).
- Utilised different visualization tools to showcase the correlation between different features and the the target variable.
- Built 3 different models to be trained and tested by the training and testing data. (Random Forest Classifier, KNN, Xgboost)

## Code and Resources used:-

1. **Python Version**: 3.10.13
2. **Packages used**: pandas, numpy, matplotlib, seaborn, sklearn
3. **for dataset**: Visit Kaggle.com
4. **ChatGTP**: Had to utilize a bit chatGTP. The idea of using RandomSearchCV was adopted from there.

## EDA:-

![image](https://github.com/anurag122002/Customer_Segmentation_Analysis/assets/111629651/24ecd0fb-4a3f-4a0c-be93-9c476e83d4e4)

![image](https://github.com/anurag122002/Customer_Segmentation_Analysis/assets/111629651/0b64c2b2-585d-4d95-9313-68bec0de5ad2)


## Data Cleaning and Feature Engineering:-

- As the normal data cleaning procedure goes..Finding null values deleting them. Two columns I thought were unnecessary, The 'ID' and 'Var_1' columns therefore I dropped them.
- Made seperate lists for categorical and numerical variables. Utilised them by mapping the binary cateogrical variables as 0 and 1.
- There were two columns with non-binary categorical variables. therefore created dummies off those.
- For numerical varibles utilised MinMaxScaling so as to bring them under same scale.
- Mapped the target varibles (A, B, C, D) as (1, 2, 3, 4) for better model fitting and performance.

## Model Building:-

1. As the testing dataset was provided, therefore didn't care to split the dataset.
2. Trained 3 different models:- RandomForestClassifier, KNN, XGBoost
3. For validation I made a classification report for all three of the models as the validating parameters namely:- Accuracy, Precision and Recall for me are the best for specualting the performance of the model as they are both simple and to the point.
   


