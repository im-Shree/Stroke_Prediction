
# Stroke_Prediction
## Stroke Prediction model using PCA.
### We build different classification models to predict if the patient will have a Stroke based on other health features.
### We will use PCA (Principal component analysis) to reduce dimensionality of data and observe the impact on accuracy of different models we have build over the provided data.

## Libraries used:
    numpy
    pandas
    matplotlib
    seaborn
    missingno
    sklearn
## Data Reading
    Training data matrix: (43400, 12)
    Test data matrix: (18601, 11)

## Data Cleaning
    Removal of 'na' or missing values
    before:
    ![image](https://user-images.githubusercontent.com/90651908/216784876-835543ab-a354-4384-9b5b-190534bf9b6a.png)
    after:
    ![image](https://user-images.githubusercontent.com/90651908/216784901-1bcb23c3-7050-4d31-b6ca-54e020a5d02e.png)

## Pattern recognition: Establish correlation between different features in data like Gender, Smoke status.

## Label encoder: To convert different data types present in given train and test data into integer format. 

## Data split:
  Train_data: 70%
  Test_data: 30%
 
## Classification models:
    1. Naive Bayes
    2. Decision tree
    3. Random forest
    4. MLP from Neural Network
    
 ## Calculate Cross validation score for all models to compare accuracies.
 
 ## Applying principal component analysis to reduce dimensionalty of features.
    Run all models with reduced dimensions data
    Observe impact of accuracy of all models
    
 ### Conculsion
    
      Based on model performances on data after reducing feature dimensions by applying PCA, Random forest model registers a significant amount of increment of accuracy.
