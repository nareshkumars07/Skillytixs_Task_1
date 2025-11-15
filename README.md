# Skillytixs_Task_1
Task 1: Data Cleaning and Preprocessing.  Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent  formats).  Tools: Excel / Python (Pandas).

**PART 1**
**About Dataset**
**Context**
**PROBLEM_STATEMENT**

Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

**Content**
**Attributes**

**PEOPLE**

ID: Customer's unique identifier
Year_Birth: Customer's birth year
Education: Customer's education level
Marital_Status: Customer's marital status
Income: Customer's yearly household income
Kidhome: Number of children in customer's household
Teenhome: Number of teenagers in customer's household
Dt_Customer: Date of customer's enrollment with the company
Recency: Number of days since customer's last purchase
Complain: 1 if the customer complained in the last 2 years, 0 otherwise

**PRODUCTS**

MntWines: Amount spent on wine in last 2 years
MntFruits: Amount spent on fruits in last 2 years
MntMeatProducts: Amount spent on meat in last 2 years
MntFishProducts: Amount spent on fish in last 2 years
MntSweetProducts: Amount spent on sweets in last 2 years
MntGoldProds: Amount spent on gold in last 2 years

**PROMOTION**

NumDealsPurchases: Number of purchases made with a discount
AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

**PLACE**

NumWebPurchases: Number of purchases made through the company’s website
NumCatalogPurchases: Number of purchases made using a catalogue
NumStorePurchases: Number of purchases made directly in stores
NumWebVisitsMonth: Number of visits to company’s website in the last month

**PART 2**

**DATA CLEANING PROCESS**

**STEP 1 :**
Understanding the nature of the dataset by analysing the problem statement and the columns of the datasets.

**STEP 2 :**
Import the pandas as pd.

**STEP 3 :**
Import dataset in notebook.

**STEP 4 :**
Perform operations like describe, head, columns, shape, info, isnull to analyse the dataset and understanding the nature of the dataset.

**STEP 5 :**
Copied the dataset to perform operations hence it make sures that datas will be safe incase of any wrong operations performed.

**STEP 6 :**
Performing operations with the copy dataset like drop duplicates and removing the nulls and unwanted columns.

**STEP 7 :**
In this dataset, I had removed the Z_CostContact and Z_Revenue which does not need for the data analysis and visualization.

**STEP 8 :**
Downloading the cleaned Dataset.
