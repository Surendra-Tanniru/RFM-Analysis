# Customer Segmentation based on RFM Analysis

Adventure Works Cycles a multinational manufacturing company. The company manufactures and sells metal and composite bicycles to North American, European and Asian commercial markets

# Data Understanding

AdventureWorksDW2019.bak can be downloaded from internet.

  Built 5NF STAR Schema(Fact, Customer, Product, Date, Location) from the database imported

![image](https://user-images.githubusercontent.com/83650174/122660067-b0b94500-d19b-11eb-933a-ef66460b553a.png)

# Data Preparation

Built SQL Queries from the tables to get orders  done by different customers in the year 2013

Calculated R, F and M values for each customer  from the data generated with reference date 


Depending on the company’s objectives, customers can be segmented in several ways so that it is financially possible to make marketing campaigns. 

The ideal customers for e-commerce companies are generally the most recent ones compared to the date of study (our reference date), who are very frequent and who spend enough.

![image](https://user-images.githubusercontent.com/83650174/122660109-20c7cb00-d19c-11eb-8fc6-2c7155e65a34.png)

Based on the RFM values, we assigned a score to each customer between 1 and 3 for each RFM value of a customer.  3 is the best score. 1 is the worst score

Ex : A Customer who bought most recently and most often, and spent the most, his RFM score is 3–3–3

![image](https://user-images.githubusercontent.com/83650174/122660117-31784100-d19c-11eb-8bd5-37a3f2c5d489.png)


# Recommendations

Best Customers: We can Reward them for their multiples purchases. They can be early adopters to very new products. Suggest them “Refer a friend”. Also, they can be the most loyal customers that have the habit to order.

Lost Cheap Customers: Send them personalized emails/messages/notifications to encourage them to order.

Big Spenders: Notify them about the discounts to keep them spending more and more money on your products

Loyal Customers: Create loyalty cards in which they can gain points each time of purchasing and these points could transfer into a discount


# Conclusion :

Naive Bayes has an Accuracy of 95% and 84% of Area under ROC but the TP rate is 0

Logistic Regression has an Accuracy of 95% and 84% of Area under ROC but the TP rate is 0

Decision Tree Model has an Accuracy of 95% and 84% of Area under ROC but the TP rate is 3.3%

Where as Random Forest Model has an Accuracy of 96% and 84% of Area under ROC but the TP rate is 12.5%

So, Random Forest Model is better in identifying the customer segments that we need to target in our dataset 

