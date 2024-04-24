
# Diabates Prediction 

## Problem Setting:
Diabetes is a chronic (long-lasting) health condition that affects how your body turns food into energy. Your body breaks down most of the food you eat into sugar (glucose) and releases it into your bloodstream. When your blood sugar goes up, it signals your pancreas to release insulin. Insulin acts like a key to let the blood sugar into your body’s cells for use as energy. With diabetes, your body doesn’t make enough insulin or can’t use it as well as it should. When there isn’t enough insulin or cells stop responding to insulin, too much blood sugar stays in your bloodstream. Over time, that can cause serious health problems, such as heart disease, vision loss, and kidney disease. The World Health Organization (WHO) estimates that 422 million people worldwide have diabetes, mostly in low- or middle-income nations. And up until the year 2030, this might be increased to 490 million.

## Problem Defination:
The only method of preventing diabetes complications is to identify and treat the disease early. The early detection of diabetes is important because its complications increase over time. Also, the prediction of diabetes at an early stage can lead to improved treatment. The intention of this project is to build supervised models like Logistic regression, K nearest neighbors, Support Vector Machines, Random Forest, and Decision trees and select the best algorithm which can perform early prediction of diabetes for a patient with high accuracy and analyze the variables which are more responsible for causing diabetes.

## Data Source:
The dataset for diabetes prediction has been taken from Centers for Disease Control and Prevention (CDC) submitted by National Center for Health statistics (NCHS) as part of National Health and Nutrition Examination Survey (NHANES) conducted in the year 2013-2014.

https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?BeginYear=2013





## Data Description
This dataset comprises a total of 9456 instances joined from multiple datasets such as Diet data, Lab data, Demographic data. There are a total of 27 attributes some of which are Age, BMI, Systolic Blood Pressure, Total Cholesterol, Glycohemoglobin and 1 target attribute - ‘Diabetes’.

![Image](https://github.com/Kandukuri-Nikhil/Diabetes-Prediction-ML/blob/main/Images/Picture1.png?raw=True)


## Data Mining Tasks
### Data Partitioning and Balancing Data using SMOTE:

- Holdout Method was used with a 70:30 ratio to split the data into training and testing sets.
- Training set (X_train and y_train) with 4650 records was used for model training, while testing set (X_test and y_test) with 1993 records was used for model evaluation.
- The original data set had an imbalanced distribution with few data points labeled as "1" (diabetes) and majority labeled as "0" (non-diabetes).
- SMOTE over-sampling technique was applied to the training data to address class imbalance, resulting in equal distribution of minority and majority classes with 4,228 data points each.


| Before OverSampling | Counts |
|----------------------|--------|
| Label '1'            | 422    |
| Label '0'            | 4228   |

| After OverSampling | Counts |
|---------------------|--------|
| Label '1'           | 4228   |
| Label '0'           | 4228   |

And the shapes of the data after OverSampling:

- After OverSampling, the shape of train_X: (8456, 25)
- After OverSampling, the shape of train_y: (8456,)

## Project Results

![Image](https://github.com/Kandukuri-Nikhil/Diabetes-Prediction-ML/blob/main/Images/Picture3.png?raw=True)









