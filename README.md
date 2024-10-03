# Customer Personality Analysis 🤓📊
Kaggle Dataset Link https://www.kaggle.com/imakash3011/customer-personality-analysis

## Context 📜:
Customer Personality Analysis involves an in-depth examination of a company’s customer base better to understand their behaviors, preferences, and needs. This analysis allows businesses to tailor their products and marketing strategies to specific customer segments, leading to more targeted and efficient decision-making.
![image](https://github.com/user-attachments/assets/e877c9dc-187f-4cec-8bf2-9bacf13d334a)


## Problem Statement 🚨:
How can a company segment its customers based on their personalities and buying behaviors? The goal is to cluster customers and determine how different groups respond to marketing campaigns, thus enabling companies to focus their efforts on high-potential segments.


## Attributes 📃:
ID: Customer's unique identifier
Year_Birth: Customer's birth year
Education: Customer's education level
Marital_Status: Customer's marital status
Income: Customer's yearly household income
Kidhome: Number of children in the customer's household
Teenhome: Number of teenagers in the customer's household
Dt_Customer: Date of customer's enrollment with the company
Recency: Number of days since customer's last purchase
Complain: 1 if customer complained in the last 2 years, 0 otherwise
## Products:
MntWines: Amount spent on wine in last 2 years
MntFruits: Amount spent on fruits in last 2 years
MntMeatProducts: Amount spent on meat in last 2 years
MntFishProducts: Amount spent on fish in last 2 years
MntSweetProducts: Amount spent on sweets in last 2 years
MntGoldProds: Amount spent on gold in last 2 years
### Promotion:
NumDealsPurchases: Number of purchases made with a discount
AcceptedCmp1 - AcceptedCmp5: Indicates if the customer accepted offers in campaigns 1 to 5, respectively
Response: 1 if the customer accepted the offer in the last campaign
### Place:
NumWebPurchases: Purchases made through the company's website
NumCatalogPurchases: Purchases made using a catalogue
NumStorePurchases: Purchases made directly in stores
NumWebVisitsMonth: Visits to the company’s website in the last month
## Target 🎯:
Perform clustering to segment the customers and summarize their behaviors. The main questions we aim to answer are:

What do customers say and feel about the product?
What actions do customers take in relation to the product?
Approach 🪧:
Data Collection & Cleaning:

Collected data from Kaggle.
Conducted exploratory data analysis (EDA) to inspect the dataset’s structure (columns, rows, missing values).
Imputed missing values using the mean.
Grouped similar columns and dropped non-useful ones.
Exploratory Data Analysis & Visualization:

Visualized key binary attributes using count plots (e.g., campaign acceptance rates).
Used matplotlib, seaborn, and plotly for creating visualizations.
Clustering (K-Means):

Applied K-Means clustering to group customers into segments.
Used the Silhouette method to identify the optimal number of clusters.
Reporting & Visualization:

Analyzed customer segments based on key attributes such as age, income, and product preferences.
Generated visualizations to display cluster characteristics and responses to marketing campaigns.

Tableau Dashboards:
Created two Tableau dashboards based on the cleaned datasets at different stages.

This dashboard explores deeper insights into customer behavior over time, responses to marketing campaigns, and website engagement.
## Conclusion:
Using customer segmentation, businesses can improve their product marketing strategies, target high-potential customer groups, and streamline customer engagement.
By analyzing customer behaviors and responses to campaigns, businesses can better anticipate the needs of their customers and create personalized experiences.

Follow me on Linkedin  https://www.linkedin.com/in/mohan-krishna-kola/
Thank you for exploring! ⭐
