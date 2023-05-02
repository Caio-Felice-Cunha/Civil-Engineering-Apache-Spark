# Machine Learning in Civil Engineering with Apache Spark
The development of our own AutoML system, without using specific frameworks and applying Machine Learning with Spark MLlib in PySpark

![image](https://user-images.githubusercontent.com/111542025/235374693-dece2ee5-3459-494b-97f2-764632f8e977.png)

## This is the 1st version

## Business Problem
> Data source: [Concrete Compressive Strength Data Set](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength).

Concrete is the most important material in Civil Engineering. The compressive strength of concrete is a highly non-linear function of age and the ingredients used to prepare the concrete.<br>

Our job will be to build a predictive model capable of predicting concrete strength based on a series of concrete characteristics and ingredients.

## Solution Strategy
The “Concrete compressive strength” variable (csMPa column in the dataset) will be our target variable and the others will be the predictor variables.<br>

As we are going to predict a numerical value that represents the strength of the concrete and we have input and output data, this is a regression problem. Let's try different regression algorithms and choose the one that performs best. Hyperparameter optimization techniques will be explored to arrive at the best possible model.<br>

With the trained model we will make predictions using new data.
* Step 01: Preparing the Spark Environment and Loading the Dataset;
* Step 02: Data Preparation Automation Module;
* Step 03: Split on Training and Test data;
* Step 04: AutoML (Automated Machine Learning) module;
* Step 05: Making Predictions with the Trained model.

## Next Steps
* Accepting suggestions.

## Disclaimer
This project was largely done in the Data Science Academy, Big Data Real-Time Analytics with Python and Spark course (part of the Data Scientist training)
