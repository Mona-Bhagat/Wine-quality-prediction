# Wine-quality-prediction using Random Forest

![Capturewine](https://github.com/Mona-Bhagat/Wine-quality-prediction/assets/148805047/b325a63e-bd5f-4fe6-b90e-8431a2e5e176)


# Project Overview
This project aims to build a Wine quality Prediction system using the Machine Learning algorithm - Random Forest Classifier 

# Data Sources
The primary dataset used for this analysis is the multivariate type of dataset "wine quality" file. The dataset is publicly available on link - https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
The model predicts the quality of wine based on physicochemical tests  (fixed acidity, citric acid) and the output variable is 'qyuality' (score between 0 and 10)  


# Tools
	• Excel CSV
 	• Google Colab
  • Following dependencies/libraries were imported:
  * pandas
  * numpy
  * matplotlib
  * seaborn
  * from sklearn.model_selection import train_test_split
  * from sklearn.ensemble import RandomForestClassifier
  * from sklearn.metrics import accuracy_score
  
# Steps involved

* Import of required libraries
* import of data
* Checking for any missing values
* Finding the correlation b/w feature variables and the target variable
* Separating the data into features and Target
* Label Binarization. Required as target variable had score b/w 0 to 10. Hence scores above were binarized as '1', and scores less than '7' were binarized as '0' 
* Splitting the data into training and test data
* Model training using Random Forest Classifier Model
* Model evaluation using accuracy score
* Building a Predictive system with our trained model


# Results
The analysis results are summarized as follows:
* Accuracy score on Test Data:  0.934375
* The model build was able to correctly recognize the presence of diabetes with sample data 
