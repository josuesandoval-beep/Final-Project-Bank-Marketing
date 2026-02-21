# Final-Project-Bank-Marketing
   This project is a part of the AAI-500-02 course in the Applied Artificial Intelligence Program at the
University of San Diego (USD).

-- Project status: Completed

## Installation
   Preinstillation of ucimlrepo is required to fetch the dataset. This is included in the Jupyter Notebooks code but if issues occur then refer to: https://github.com/uci-ml-repo/ucimlrepo for further detailed set up instructions.

## Project Objective
   The main purpose of the project is to assess the development of an end-to-end statistical analysis by finding a dataset, clean and prepare it for analysis, perform EDA, and produce a model. We then produce a final technical report discussing the results of the analysis and the validity of the models selected.  
   
### Contributors 
- Janelle Stradford , Niraj Chandarana , Josue Sandoval

### Methods Uused
 - Data Visualization
 - Machine learning
 - Binary Classification

### Technologies 
 - Python
 - Colab
 - Jupyter Notebooks

## Project Description
   Utilizing UCI's Bank Marketing dataset, we analyze 16 feature variables to predict whether a client subscribed to a term deposit (target variable). The data is related with direct marketing campaigns of Portugese banking institutions. We utilize univariate data analysis to decribe each feature's distribution and count frequency, which provids information on which features are skewed. We also utilize bivariate data analysis to compare the relationship between the independent variables and the dependent variable. We split the data into training and testing sets, to fit the models to the training data and evaluate the models on the testing data. We train four models: Logistic Regression, Random Forest Classifier, Gradient Boosting Classifier and Support Vector Classifier. We compare the following metrics: accuracy, precision, recall, f1-score, and AUC. The dataset's dependent variable is imbalanced with negative results make up the majority class at about 88%. This imbalance imparts a bias in the models towards predicting for the majority (negative) class, resulting in low recall in all the model. Further techniques that reduce imbalance effect could be explored to improive minority class prediction.    
