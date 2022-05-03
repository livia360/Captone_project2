
Understanding Superstore's Sales data using EDA
======================================================
  
![Sales] (./images/sales.jpg)


# 1. Introduction

With growing demand in the market, a Supertore giant likes to have a better understanding of what factors matter to the sales and profits, accordingly to improve the forthcoming sales stragety.

The dataset is from [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) and was collected between Jan. 2014 and Jan. 2018.



The capstone project contains four parts: data cleaning, exploratory data analysis, preprocessing, final model selection and prediction.

# 2. Data Cleaning and Wrangling

  
![Sales_profits_order_by_state](./images/total_profits.png)
![Sales_profits_by_state](./images/barh_sales.png)

# 3. Exploratory Data Analysis


  
![Profit_total](./images/profit_total.png)
![Profit_pos](./images/profit_pos.png)
![Profit_negl](./images/profit_neg.png)
![Profit_neg_causel](./images/profit_2states.png)

**Heatmap gives us a sense of the important features to the profits**
![correlation](./images/heatmap.png)  



**Words heavily involoved in product names**
  

![wordcloud](./images/text.png)  
 



# 4. Preprocessing 
  


![PCA](./images/pca1.png)

**The first two components account for about 60% of the variance, and the first five for over 85%.**   
  
![PCA colored by avg_profits](./images/pca2.png)

The red points represent the upper quartile of 'profit' and spread across the first dimension (>0).

# 5. Training and Modeling



![top 5 important features](./images/important_features.png)


