# GreyAtom-Hackathon
Providing the solution of Credit Consumption Prediction Hackathon conduced by GreyAtom School Of Data Science

Problem Statement :-

Credit card consumption patterns are a gold mine for banks and financial companies. The consumption patterns and spends of a customer allow banks to build strategic partnerships with vendors for discounts or other plans to reward and retain customers. Further, banks can understand from the spending patterns and profile people based on spending and tailor the loans or financial products based on those.

Thus it is important to understand the relationship between the customer profile and their spending patterns. The Common Man Bank Ltd (CMB) wants to understand these patterns thoroughly and get insights on the customer persona and the spending patterns. So from their database, they have prepared the data of sample customers and their transaction history. As a data scientist working with CMB, you are now supposed to mine insights from the data.

CMB Bank has given customer details, like age, gender and other demographics. Also shared are information on liabilities, assets and history of transactions with the bank for each customer. In addition to the above, data has been provided for a particular set of customers' credit card spend in the previous 3 months (April, May & June) and their expected average spend in the coming 3 months (July, August & September). Predict the average spend for a different set of customers in the test set for the coming 3 months.


Datasets:-

1.Train.csv - It is the training data containing the features of customers, along with their average credit card spend for the next three months.
2.Data_Dictionary.xlsx - It contains a brief description of every variable provided in the training and test set.
3.Test.csv: - It contains details of the customers for which the participants need to predict the average spend for the next three months
4.sample_submission.csv - This is a sample file of the format in which you have to submit your predictions.


Evaluation Criteria:-

The average predicted spend of customers for the next three months would be evaluated using Root of Mean Squared Logarithmic Error i.e RMSLE.