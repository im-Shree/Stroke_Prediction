## Stroke Prediction Machine Learning Project
This is a machine learning project to predict whether a person is likely to have a stroke or not based on certain features like age, gender, smoking status, etc. Four different algorithms have been used to create the models - Naive Bayes, Decision Tree, Random Forest, and MLP from Neural Network and PCA.

## Dataset
The dataset used for this project is the Stroke Prediction Dataset from Kaggle. It contains information about patients and whether they have had a stroke or not. The dataset has 5110 rows and 12 columns.

## Requirements
This project requires Python 3.x and the following libraries:

    pandas
    numpy
    scikit-learn
    matplotlib
    seaborn
    keras

## You can install the required libraries using pip:

    pip install pandas numpy scikit-learn matplotlib seaborn keras

## Files: The project consists of the following files:

    stroke_prediction.ipynb: Jupyter notebook containing the implementation of 
        Naive Bayes algorithm
        Decision Tree algorithm
        Random Forest algorithm
        MLP from Neural Network 
        PCA algorithm for dimensionality reduction
        
    test_2v.csv: CSV file containing the test dataset after split.
    train_2v.csv: CSV file containing the test dataset after split.

Usage

    To run the project, first, download the dataset and save it as stroke_data.csv. Then open the Jupyter notebooks and run the cells. 
    The notebooks contain explanations and code for data preprocessing, model building, and evaluation.

Results

    The results of the models are compared using accuracy, precision, recall, and F1-score. 
    The best-performing model is Random Forest with an accuracy of 0.9539 and an F1-score of 0.486.

Conclusion

    In this project, we have seen how to use different machine learning algorithms to predict the likelihood of a person having a stroke. 
    We have also seen how to evaluate the models using various metrics. 
    Random Forest has shown the best results in this case, but other algorithms can also be used depending on the specific requirements of the problem.
