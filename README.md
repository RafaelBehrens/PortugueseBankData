# Portuguese Bank Marketing Data Analysis

Running a machine learning analysis on Portuguese bank data to evaluate a customer's likelihood of subscribing to a term depsoit.

## Summary

Evaluate subscription likelihood using a Random Forest model. Data exploration, feature engineering and building a machine learning model. Evaluate dataset using F1 Score/Confusion Matrix/Accuracy Score.

## Data

The data was sourced from [this Kaggle competition](https://www.kaggle.com/henriqueyamahata/bank-marketing), which in turn references [this academic article](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing#)

The academic article runs their own regression on the Portuguese bank data. 

The definitions of the columns are available in bank-additional-names.txt

## Approach

1. Exploratory analysis of the dataset itself, evaluating the types of data available, examining the data types separately.

2. Evaluate the distribution of the variables: age, marital status, pdays, consumer price indices etc. using violin plots and histograms.

3. Apply dummy variables for the categorical data (job, marital, education, poutcome).

4. Map boolean data to 1 & 0.

5. Cleanse N/A values.

6. Split data into training and test sets.

7. Feature impute and scaling

8. Evaluate a Random Forest model on the dataset, evaluate 10 most important features. 

9. Experiment with further machine learning models. 

10. Evaluate data, measuring accuracy.


## Built With

SKLearn, Jupyter Notebook, Seaborn, Numpy, Pandas

## Authors

Fede Behrens

## Acknowledgments

* Thanks to the [Costa Rican Household Poverty Level Prediction Kaggle Competition](https://www.kaggle.com/c/costa-rican-household-poverty-prediction) for some of the methods and approach. 
