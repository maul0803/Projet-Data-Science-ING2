# Project F8: Binary Prediction

The project comes from a Kaggle competition: Binary Prediction of Smoker Status using Bio-Signals

**Authors:** Côme Quintyn, Kathleen Guillet

**Goal 1:** Develop a Machine Learning model with an AUC of at least 80%, to predict the smoking status of a person using bio signals.

**Goal 2:** Find correlations between features and labels and improve models (time taken to create the model, AUC…).

***

## In this repository can be found:

  -**F8_report** which contains the Business understanding, the Data understanding and the plan that had been followed to achieve this project.
  
  -**F8_notebook** which contains the code used to get our results.

  -**Train.csv** : the data from Kaggle competition to train the models.

  -**Test.csv** : the data from Kaggle competition to test the models.


***

## Info about the code

This is a step-by-step guide to understand and replicate the same experiment from our own.

1. Download the notebook file (its opening and usability are supported in the Colab environment)
2. Do not run all the notebook at once (it contains a few gridSearchCv methods that can take hours to be run)
3. It is defined in several parts: configuration, Exploratory Data Analysis, preparation of the data, training and tuning of the models and some analysis about the results and the data 
4. Upload the required data from this repository to the cell in the notebook made for this purpose
5. If you want to use the command to make a submission on Kaggle, upload also the json file where it is asked, else you can still do it manually
6. The following cells are for taking a look at the data, the columns, the distribution, the types of the attributes and also if there are any anomalies
7. Then some data balancing is done with different methods
8. Tuning the majority of the models is done with the gridSearchCv method
9. After each tuning and training of every model, a prediction is made on the test set and is input in a csv file which is submitted in Kaggle thanks to the command
10. Finally, all results are presented in a conclusive plot at the end, and to look more into the data, some analysis of the features and their importance for the prediction are made, with a correlation circle and matrix.
