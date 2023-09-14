# NLP-Auto-ticket-classifier

## Problem Statement 

We need to build a model that's able to classify customer complaints based on the products or services. By doing this, we can divide these tickets into their relevant categories and therefore, help in the quick resolution of the complaint.

we will be doing topic modelling on the <b>.json</b> data provided by the company. Since this data is not labelled, we need to apply Non-Negative Matrix Factorisation (NMF) to analyse patterns and classify tickets into the following five clusters based on their products or services:

* Credit card / Prepaid card

* Bank account services

* Theft / Dispute reporting

* Mortgages / loans

* Others 


With the help of topic modelling, we will be able to map each complaint ticket onto its respective category. we can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, we can classify any new customer complaint support ticket into its own relevant department.
