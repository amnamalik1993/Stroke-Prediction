<img width="725" alt="image" src="https://user-images.githubusercontent.com/124516948/227580494-a2aa9632-a720-4777-9778-6b63678b325d.png">


# Stroke Prediction And Insights
### Analyzing Risks and Factors That Cause Stroke
**Author: Amna Malik**

### Business problem:
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient. The problem is how to prevent from increasing number of stroke patients associated with all these features.

### Data Source:
The url for the data: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

For this dataset, there were 5110 rows and 10 columns.

## Data Preparation

- The data was cleaned. Duplicates were removed. Missing values were imputed. 
- Visualizations were made to demonstrate different findings.

## Exploratory Analysis


- Many visualizations were created to get further understanding of the dataset. Histogram was visualized for each different datatype columns. 
- This gave a good baseline for all of the numeric and categorical columns for univariate EDA.

<img width="431" alt="image" src="https://user-images.githubusercontent.com/124516948/232090451-2cb4ce5b-69b2-4bd9-b810-1d54e0536064.png">

## Explanatory Data Analysis

- To visualize the data for explantory purposes, many bargraphs were chosen and one pie chart was chosen.
- The bargraphs were chosen to show how the categories compare to each other. 

<img width="409" alt="image" src="https://user-images.githubusercontent.com/124516948/232091388-3901137d-02c0-4fb4-98ed-cf4fad2b5e5e.png">

## Maching Learning Using the Following Models:

- Random Forest Regressor
- Tuned Random Forest
- Decision Tree Regressor Model
- Tuned Decision Tree Regressor Model

Training Scores for High Variance RF
Results for training data:
  - R^2 = 0.636
  - RMSE = 0.118



Testing Scores for High Variance RF
Results for testing data:
  - R^2 = 0.085
  - RMSE = 0.211
  
 ## Recommendations:

The final recommedation would be the Random Forest Tree Regressor Model.

This model performed well on the testing data after tuning it.

It did lead to poor performance of training set after tunning the model. However it showed improved results with the testing data.

There was still some bias in the model, but by far it outperformed the than Decision Tree Regressor Model.

## Next Steps

Further modelling can also be performed like Linear Regression that may show different results. 


### For further information


For any additional questions, please contact **amna.malik10@hotmail.com**





  
  
  
 

