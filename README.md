# Vinay_Portfolio

# Data Science Project examples

## [Project 1: Identify External Features Affecting Product Sales (Correlation, Regression and XGBoost)](https://github.com/vinayamsnl/Data-Science-Projects)

* In this example I analysed beer sales data and quantitatively assessed the impact of features like average day temperature, hours of day light and holiday indicator
* Analyzed correlation between beer sales, hours of daylight, average temprature. Also detected the problem of multicollinearity
* Built a regression model with given features impacting beer sales and used this model to predicte next months sales 
* Explored how multicollinearity effect model by building two regression models (statsmodel library), one with highly collinear variables and another after excluding one of the collinear variables
* Created new features (time based) that could possibly effect the sales
* Built a Xgboost regression model with new features and produced a list of top feature impacting bear sales

![](/Images/Regression.png)


## [Project 2: Cancer Tumour Classification (EDA and SVM Model)](https://github.com/vinayamsnl/Data-Science-Projects)

* In this use case I analysed cancer tumours data comprises of 30 features derived from cancer cell images and built a classification model to classify malignant and benign cancer tumour types 
* Prepared data for model training and visualised target and predictor variables
* Built classification model using SVM (Support Vector Machine) with 95% plus accuracy
* Also impemented model parameter tunning by detecting best model parameters to improve model's accuracy
* Produced model performance statistics such as recall, precesion, f1-score and accuracy 

![](/Images/confusion_matrix.png)

## [Project 3: Customer engagement analysis (Logistic Regression)](https://github.com/vinayamsnl/Customer-Analysis-Project)

* In this case study I analysed a fin-tech company's customers and transactions data to get insight into customer enegagment with their product
* Prepared data related customers, transaction , notifications and devices to get insight into customers usage patterns and types of engagements
* Deep dived into data by perforing exploratory data analysis to identify the important features effecting the customer engagement using Weight of Evidence (WOE) and Information Value(IV)
* Performed variable binning for categorical variables with large number of categories
* Built a logistic regressionmodel to predict the chances of customer churn using their customers data along with transactions, notifications data containing notifications to customers and devices data 

![](/Images/ROC.png)

