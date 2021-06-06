## Project Name: Stroke Predicton
To mitigate the stroke risk, it is urgent to provide a way to accurately predict the stroke risk of a person given a set of attributes, such as examination data, medical history, and demographic information. In this project, I explored different machine learning models on a stroke risk dataset, aiming to optimize the predicting power.

## Installation
The code requires Python versions of 3.* and general libraries.

## Project Motivation and Description
A stroke is a serious life-threatening medical condition that happens when the blood supply to part of the brain is cut off. Stroke is also a leading cause of serious long-term disability. Because of the life-threatening nature of stroke, it is extremely important to take early action. Know the warning signs and symptoms of stroke so that one can act fast if you or someone you know might be having a stroke. The chances of survival are greater when emergency treatment begins quickly. In addition, high blood pressure, high cholesterol, smoking, obesity, and diabetes are generally regarded as leading causes of stroke, while 1 in 3 adults in the United States has at least one of these conditions, making the prediction of stroke risk even more important as compared to other population without these conditions.
To mitigate the lethal threat of stroke, accurate models being able to predict the stroke risk are urgently need. In this project, I trained machine learning models on a data set of strokes with information of gender, age, hypertension, heart disease history, marital status, work type, residence type, average glucose level, bmi, smoking status, the best f1-score achieved is xxx, providing a reliable way to predict the stroke risk using the aforementioned person information.

### Three different models I used in this project.
* Logistic Regression
* Random Forest Classifier
* xgboost Classifier

## Results
In this project, I performed logistic regression, random forest and xgboost classifications on a stroke risk dataset. F1-score and auc-roc score were used as the metric for performance evaluation, and the best f1-score obtained in 0.238 from logistic regression, while the best auc-roc score is 0.809 from the xgboost model. Even though the auc-roc score is not so bad, the patients with stroke are not well classified, which will not benefit the process of early intervention to mitigate the stroke risk, the problem is likely due to the highly imbalanced dataset. 
