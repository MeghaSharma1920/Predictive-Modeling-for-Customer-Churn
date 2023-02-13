# Predictive-Modeling-for-Customer-Churn

Assignment: Predictive Modeling for Customer Churn.

Objective:
The objective of this assignment is to build a predictive model that can predict customer churn for a given company. 

We used machine learning techniques to build the model and document the process, including feature selection, model evaluation, and performance metrics.

Instructions:

1.	Obtain a dataset of customer information, including demographic information, customer behavior, and whether or not the customer has churned.

2.	Perform data cleaning and preprocessing on the dataset, including handling missing data and converting categorical variables to numerical variables.

3.	Explore the data and perform feature selection to select the relevant features that will be used in the model.

4.	Build a predictive model using machine learning algorithms such as Logistic Regression, Random Forest, or Gradient Boosting.

5.	Train the model using a portion of the data and use the remaining data to evaluate the performance of the model.

6.	Evaluate the model performance using metrics such as accuracy, precision, recall, F1-score and AUC-ROC.


# Dataset
7. Relevant Information:

   The data is related with direct marketing campaigns of a Portuguese banking institution. 
   
   The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required,in order to access if the product (bank term deposit) would be (or not) subscribed. 

   There  dataset used is bank.csv with 10% of the examples (4521), randomly selected from bank-full.csv.
    

   The classification goal is to predict if the client will subscribe a term deposit (variable y).
   1) Number of Instances: 45211 for bank-full.csv (4521 for bank.csv)

   2) Number of Attributes: 16 + output attribute.
   
   3) bank client data:
  
   1 - age (numeric)
   
   2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student","blue-collar","self-employed" , "retired" ,"technician","services") 
   
   3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
   
   4 - education (categorical: "unknown","secondary","primary","tertiary")
   
   5 - default: has credit in default? (binary: "yes","no")
   
   6 - balance: average yearly balance, in euros (numeric)
   
   7 - housing: has housing loan? (binary: "yes","no")
   
   8 - loan: has personal loan? (binary: "yes","no".related with the last contact of the current campaign:
   
   9 - contact: contact communication type (categorical: "unknown","telephone","cellular") 
   
  10 - day: last contact day of the month (numeric)
  
  11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
  
  12 - duration: last contact duration, in seconds (numeric)
  
  13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
  
  14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
  
  15 - previous: number of contacts performed before this campaign and for this client (numeric)
  
  16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

  Output variable (desired target):
  
  17 - y - has the client subscribed a term deposit? (binary: "yes","no")
  

8. Missing Attribute Values: None


