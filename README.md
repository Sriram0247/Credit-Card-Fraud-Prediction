## Objective
The purpose of this project is to predict the probability of credit card fraud. Given the severe class imbalance in the dataset, the main evaluation metric is the Area Under the Precision-Recall Curve (AUPRC).

### Methods used
* Inferential statistics
* Machine Learning
* Data Visualization
* Predictive Modelling

### Technologies
* Python, Jupyter

## Project Description
* The dataset used for this project is the “Credit Card Fraud Detection” dataset. The data represents credit card transactions that occurred over two days in September 2013 by European cardholders. The dataset is credited to the Machine Learning Group at the Free University of Brussels (Université Libre de Bruxelles) and a suite of publications by Andrea Dal Pozzolo, et al. All details of the cardholders have been anonymized via a principal component analysis (PCA) transform. Instead, a total of 28 principal components of these anonymized features is provided. In addition, the time in seconds between transactions is provided, as is the purchase amount (presumably in Euros). https://raw.githubusercontent.com/jbrownlee/Datasets/master/creditcard.csv.zip
* Repeated Stratified k-Fold Cross Validation technique is used to evaluate models. 
* This project evaluates the Decision Tree algorithm, KNN algorithm, Random Forest algorithm and Extra Trees algorithm on the dataset. The KNN algorithm outperforms all other models with the highest mean AUPRC.
* Finally, the KNN algorithm is fit on the entire dataset and predictions are made on new data of normal cases and fraud cases.
