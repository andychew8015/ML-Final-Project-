# ML-Final-Project-Telco-Churn
### Scenario:
As one of the leading telco in the country, the company are proud to provide quality services that have been receiving satisfactory feedback from customers frequently. But from recent quarterly reports, there have been a drop in the customer base.
We are instructed by the management to create a model to predict if a customer will churn so that they are able to come up with solutions to keep hold of them.
### Objective
- using dataset downloaded from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn/code)
- performed Data Cleaning, Data Pre-processing and Feature Engineering on the dataset
- trained a few baseline model and performed Hyperparameter Tuniing on the best baseline model to try and improve the result
### Required Library:
- Numpy
- Pandas
- Matplolib
- Seaborn
- Scikit-Learn
### Result:
Since we want to catch as much as possible of those customers that churned, we will be using **Recall** as our evaluation metric and the final model gives us a recall rate of **83%**.
This means out 0f 100 customers that churned, the model can predict 83 of them correctly.
