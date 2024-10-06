# SUPERSTORE ANALYSIS USING POWERBI
## Introduction
As part of assessment in the Data Science class organized by PSP Analytics, one of the analytics projects I’ll be working on is the Superstore Dataset. This superstore is located in the United States of America and they sell Furniture, Office Supplies and Technology products. The superstore dataset contains the Shipping dates, Sales, Profit and other data of the Super Store.
The goal of this work is to analyze the Superstore’s performance and to uncover insights to be used for the business growth.

## Data Sourcing 
This dataset used in this work is gotten from the Data Science Class announcement channel, which was posted by Mr. Zion Segun.
## Data Preparation 
We will load the dataset in excel format into powerbi.  If data is clean, we can just load it directly or transform it to clean it on PowerBi. 
## Data Cleaning/Transformation
Here, we check if the format of each column is correct and correct it were necessary. We also address inconsistencies in the columns to ensure a more accurate dataset for analysis
- Now, we format the Sales, Profit and Discount columns to display currency

## Data Exploration/Visualization 
This is where we answered specific business questions for sale performance analysis using charts and tiles. Some of these questions include:
1.	Which Category has the highest orders
2.	What is the profit margin accrued by each category
3.	In which city does the store have more orders?
4.	Which sub-category has more sales?
5.	What City yields more sales
### KEY PERFORMANCE INDICATORS
Before going ahead to answer the question, we first need to specify the KPI (Key Performance Indicators). The KPI include the Sales, Quantity, Profit, Profit Margin and Discount. This is done by creating measures and using DAX to calculate the total sales, profit, quantity, discount and to derive our Profit Margin
- **Sales**: We use SUM function to get total sales
**- Quantity:** SUM of quantity in the dataset
**- Profit**: SUM of profit in the data set
**- Profit Margin:** This is the calculation of total profit DIVIDED by total sales multiplied by 100
**- Discount:** SUM of total discount in the dataset
  
We the use the KPI tile to visualize our KPI. We could also use the Card tile.

**1.	Which Category has the highest orders?**

The highest order can be obtained by using the clustered column bar to draw relationship between the “Category” column and the “Quantity” measure. 
 ![image](https://github.com/user-attachments/assets/a7ca0dae-f450-4028-bce3-33aff98fc972)

**2.	What is the profit margin accrued by each category?**

 ![image](https://github.com/user-attachments/assets/5181ca11-008b-4e00-b16e-a7afeeb91c03)

**3.	In which city does the store have more orders?**

![image](https://github.com/user-attachments/assets/d604b57c-100e-4a8e-8def-675e543a09ab)
 
**4.	Which sub-category has more sales?**

 ![image](https://github.com/user-attachments/assets/327f8dea-05be-4db7-84ff-4bf99a083666)

**5.	What City yields more sales?**

![image](https://github.com/user-attachments/assets/6646dcdb-7fd5-437b-b820-75054b265fa7)

## Conclusion 
So far, we’ve been able analyze the superstore dataset and to draw valuable insights through the business questions. Based on these findings, we can be able to provide data-driven recommendations to help for business growth. The resulting dashboard built from powerbi is shown below:

![dashboard powerbi](https://github.com/user-attachments/assets/67759d1a-a220-467e-b3f3-871e8260ca3c)


