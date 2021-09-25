# CustomerAnalysis
This Jupyter Notebook is used to perform customer personality analysis following the CRISP-DM process. 

As specified in Kaggle’s website, customer personality analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors, and concerns of different types of customers.
With the use of the dataset, we are trying to give an answer to the following questions: 

-	What is the "average" customer that we are the most likely to attract in each sales campaign ?
-	What is the preferred sale channel per product ?
-	What is the profile of those customers that prefer online or catalog shopping / shopping directly in stores ?
-	What are the consumer behaviors/characteristics with the highest importance when predicting customer's yearly income ?

## Dataset 
The dataset used can be found in this repository and can be also downloaded from: 
https://www.kaggle.com/imakash3011/customer-personality-analysis
## Libraries
-	Pandas
-	Numpy
-	Sklearn
## Included files:
-	marketing_campaign.csv: dataset to be used to perform customer personality analysis 
-	Column_description.csv: containing dataset columns descriptions

## Results
While working on the customer personality dataset, we were able to extract interesting business insight that can help, in this case, the company to take better business decisions. Some examples of business insight:

- The participation of customers in sales campaigns is highly dependent on household income.
- The preferred products for customers through during the sales campaign is wine and meat, as seen in the following graphic:

![Sales campaign](https://github.com/jagutier75/CustomerAnalysis/blob/main/Product_spending_per_sales_campaign.PNG)

- The preferred sales channel varies depending on the product, and against to common belief, physical stores continue being the primary source of revenue for this company:

![Sales channel](https://github.com/jagutier75/CustomerAnalysis/blob/main/Sales_channel_by_product.PNG)

The dataset allowed us to answer to the questions stated since the beginning. Data is available everywhere and just by asking the correct questions we are half of the way of gaining business knowledge that could eventually increase profit. 

## Acknowledgements

- Thanks to Udacity team, as this exercise is part of the Data Science Nanodegree program. 
- Thanks to Kaggle for the availablity of the dataset
