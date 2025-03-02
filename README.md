# Brainwave_Matrix_Intern-Task2
# Walmart-Sales-Data-Analysis
![Sample Image](![sentiment-analysis](https://github.com/user-attachments/assets/fe8c690b-584e-43d2-b52d-d2ca2f586268)
)


## About
Walmart is a globally recognized retail giant, renowned for offering a wide range of products at competitive prices, and providing a convenient shopping experience for millions of customers worldwide.

Analyzing this dataset offers valuable insights into Walmart's customer base and purchasing behavior. It reveals details about customer demographics, product preferences, and spending patterns. This comprehensive dataset is a valuable resource for understanding various aspects of Walmart's operations, such as marketing strategies, customer segmentation, and product demand. It can enhance strategic decision-making in areas like inventory management, targeted marketing, and customer relationship management.

## Purposes of the Project
The main goal of this project is to gain understanding from Walmart's sales data, exploring the various factors that influence sales across different branches.

## Dataset Description
The dataset contains transactional data from Walmart, including details about customers and their purchases. The columns in the dataset are as follows:

* User_ID: Unique identifier for each user
* Product_ID: Unique identifier for each product
* Gender: Gender of the user (Male/Female)
* Age: Age group of the user
* Occupation: Masked occupation code
* City_Category: Category of the city (A, B, C)
* Stay_In_Current_City_Years: Number of years the user has stayed in the current city
* Marital_Status: Marital status of the user (0 = Single, 1 = Married)
* Product_Category: Masked product category
* Purchase: Purchase amount

## Project Structure :

1. Importing Libraries: Essential libraries for data analysis and visualization are imported.
  
2. Loading the Dataset: The sales data is loaded into a pandas DataFrame.
  
3. Data Preprocessing:
* Checked for duplicate and missing values.
* Data cleaning and transformation as required.
  
4. Exploratory Data Analysis (EDA):
* Analyzing customer distribution across cities.
* Examining marital status distribution.
* Identifying top-selling products and categories.
* Analyzing purchase patterns based on demographics.


## Requirements :

* Python 3.x
* pandas
* numpy
* matplotlib
* seaborn
* jupyter
  
## Conclusion :

This analysis provides valuable insights into Walmart's customer demographics and purchasing patterns, aiding in better strategic decisions in marketing and inventory management.
1. **Occupational Spending Patterns:** Occupations classified under codes 8, 12, 15, and 17 exhibit notably higher average spending, suggesting targeted marketing strategies could be effective for these groups.

2. **Top Performing Product:** The product with **Product_ID P00265242** recorded the highest purchase frequency, indicating its strong market demand and potential for promotional focus.

3. **Correlation Insights:** While no strong correlations were detected among most variables, there are minor associations between product categories and purchasing behaviors, warranting further investigation.

4. **Gender-Based Spending Variability:** Male consumers display greater variability in spending, particularly within the middle-age demographic, highlighting an opportunity for tailored marketing interventions.

5. **Product Category Performance:** **Product Category 1** emerged as the top-performing segment in terms of total purchases, underscoring its popularity and potential for driving future sales growth.

---
