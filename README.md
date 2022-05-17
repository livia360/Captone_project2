
Understanding Superstore's Sales data using EDA and Regression
======================================================
  
![Sales](./images/sale.jpg)


# 1. Introduction

With growing demand in the market, a Supertore giant likes to have a better understanding of what factors matter to the sales and profits and build a predictive model.

The dataset is from [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) and was collected between Jan. 2014 and Jan. 2018 across 48 states in the US.



The capstone project contains four parts: data cleaning, exploratory data analysis, preprocessing, final model selection and prediction.

# 2. Data Cleaning and Wrangling



- Average sales and profits by State

![Sales_profits_by_state](./images/barh_sales.png)


# 3. Exploratory Data Analysis  [(EDA)](https://github.com/livia360/Capstone_project2/blob/90f9b12ac5091c680d51271111be059c74c48747/Part1_data_wrangling_and_EDA.ipynb)


**Total Sales/Profits per State**  
![Profit_total](./images/state.png)

**Total Sales/Profits per Region**
![Profit_region](./images/region.png)

**Total Sales/Profits per Category**  
![Profit_category](./images/cat.png)

**Total Sales/Profits per Segment**
![Profit_segment](./images/seg.png)


![Profit_neg_causel](./images/profit_2states.png)


**Total Sales/Profits - Top 10 States**
![Profit_states](./images/top.png)

**Total Sales/Profits - Top 10 Cities**
![Profit_cities](./images/top2.png)



**ANOVA test** 
- ANOVA is used to estimate how the mean of a quantitative variable changes according to the levels of categorical variables. Use a ANOVA when you want to know how independent variables, in combination, affect a dependent variable.
![anova](./images/anova.png)



**Heatmap gives us a sense of the important features to the profits**
![correlation](./images/heatmap.png)  


  

![wordcloud](./images/text2.png)  
 
Through the wordcloud generated images, we can see:

- **"xerox" and "ring binder"** are the two most important words that were repeatedly mentioned in the product names. This is not very surprising since we found out 'office supplies' has the largest volumes of orders.
- Two band names that stand out from this analysis are **"newell" and "wilson jones'**, Newell Brands is an American worldwide manufacturer of consumer and commercial products with a portfolio of brands including: Rubbermaid storage, home organization and writing instruments, etc. Wilson Jones is the inventor and supplier of the three ring binder.
- **'New York'** in the east region, **'Los Angles' and ' San Francisco'** in the west region are the top three most important cities. It makes sense because they are the cities with large amount of sales of products. 


# 4. Preprocessing 
  

**PCA**
- **The first two components account for about 60% of the variance, and the first five for over 85%.**   
  
![PCA colored by avg_profits](./images/pca2.png)

The blue points represent the lower quartile of 'profit' and spread across the first dimension (>0).

# 5. Training and Modeling







