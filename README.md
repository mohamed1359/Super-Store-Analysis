# Super-Store-Analysis
## This is a project for analyzing data by using microsoft excel about store sales dataset on kaggle , aim to know the performance of sales through 4 years.



## Excel tools used:
- Needed Formulas
- Power Query
- Power Pivot(Data Modeling)
- Pivot Tables
- Pivot Charts For Visualization



## Steps followed: 
- first, present some questions to answer such as total sales through 4 years , average , max and min sales, .. 
- second, we need to extract data so we use Power Query
- third, we also use Power Query for cleaning and transforming data and split the dataset into **4 queries**:
     - `Raw Data`
     - `Orders` *(Fact Table)*
     - `Customers` *(Dimension Table)*
     - `Products` *(Dimension Table)*
- fourth, Power Pivot for data modeling use orders as fact table,(customers,products) as dimension tables and make relations between them
- fifth, data is ready so , we make summary report by using Pivot tables
- sixth, we make some data visualizations by using Pivot Charts



## Results achieved:
- total sales, average, max , min
- each year total sales and number of order for each year
- in dataset we have category and sub-category we get total sales ,count of orders of both using 1 table
- total sales for each region and states in regions, count of orders of both using 1 table
- customers is split into 3 categories(consumer,corporate,home office) we know which category is high in sales and orders
- ship mode we have 4 categories(standard class,first class,sceond class,same day) we deduct which one is mostly ordered by and make sales
- we also deduct which ship mode is mostly used in regions
- by using power query we add new column named "DaysToArrive" to get the days from order date to ship date, and we know max, min days for each ship mode and average days for each regions
- finally, we get summary report and insights to help
 


**Data Source:** [Superstore Sales Dataset on Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)


