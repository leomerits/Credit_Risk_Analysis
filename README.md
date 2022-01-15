# Credit_Risk_Analysis
# Overview of the analysis: 
In 2019, more than 19 million Americans had at least one unsecured personal loan. With the incredible growth, by using latest machine learning techniques, Fin Tech firms can continuesly analyze large amounts of data and predict trends to optimize lending. In this module we used Python to build and evaluate several machine learning models to predict credit risk.

# Resources:
- Data Source: credit_risk_resampling.ipynb, credit_risk_ensemble.ipynb, LoanStats_2019Q1.csv.
- Software: Jupyter Notebook.

# Results:
Looking at the four modules, I can say that:
- The Logistic Regression model using SMOTEEN combination re-sampler yeilded a better balanced accuracy score.
![image](https://user-images.githubusercontent.com/34757498/149609349-22e50951-51af-447e-bd85-1832fba4eb61.png)

- Both Logistic Regresion model using SMOTEEN combo re-sampler as well as using smote oversampler yielded better geometric mean score.
![image](https://user-images.githubusercontent.com/34757498/149609295-799bca8e-f1f6-4ad4-88a9-ec12f92d31f5.png)

- Logistic Regresion model using smote oversampler had a better recall score. 
![image](https://user-images.githubusercontent.com/34757498/149609224-4c6a6e0c-3cfd-49ea-b6b5-d007efdc956f.png)


# Summary:
In this module we were able with the help of the knowledge of machine learning, using varieties of credit related risk factors predict a potential client's credit risk. Also, using evaluation metrics like accuracy score, classification report and confusion matrix generated, we were able to compare models and determine which best suits a particular set of data. 
