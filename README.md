# Power-BI-Dashboard-for-Bank
This is an assessment project for Data Analyst position in a Bank

I leveraged my experience in Python and the pandas library to enhance the filtering processes and generate additional tables. Since I am more confident with Python than PowerBI for filtering large datasets, I found it to be the optimal solution for this task. I have provided a Jupyter notebook containing my Python scripts for reference.


![Screenshot from 2023-03-30 10-26-51](https://user-images.githubusercontent.com/93320620/233777006-8a65b402-42ce-4705-96fb-a11bf3fb31b5.png)

![Screenshot from 2023-03-30 10-27-07](https://user-images.githubusercontent.com/93320620/233777010-d8168096-eaa7-40da-81d6-52724e22790d.png)


![Screenshot from 2023-03-30 10-27-21](https://user-images.githubusercontent.com/93320620/233777013-8729385c-74d1-480a-b8e7-d5ed3495343c.png)


After a carefully reading the test’s description, I proceeded to perform the following data transformations: 

## Data exploration & cleaning:
    • Replaced from the “Status” column the values “Exp” with “Expired, “Rej” with “Rejected” and “Canceled Disbursed Loan” with “Canceled”, and deleted 2 null values as they don’t provide full information of the particular cases.
    • Convert the “Timestamp” column into Date type and deleted 85 null values, as they don’t provide full information of the particular cases.
    • Removed null values from Amount’s column as they don’t provide full information of the particular cases.



# PowerBI Dashboard Report: 
## Page 1: Overview
    • Created count measures for all Status characteristics:Applications Disbursed, Expired, Canceled, Rejected, the Disbursed Amount and the Sales Conversion Rate. 
    • Created a Stacked area line chart for Applications by Date and Status, and another one for Applications by Date and Product.
    • Created three donuts charts, one for Application by Status, one for Application by Product and one for Amount by Product, representing the percentage.
    • Created 3 check boxes, one for search by date with drill down-option, one for choosing each product the same for each Status. All of these boxes interacts with the rest of the charts.    
With these charts and interactive filters, the Sales Executive can gain valuable insights into the bank's performance, identifying areas for improvement and making data-driven decisions. 

## Page 2: Customer and Product Analysis
    • Penetration Rate for each product, the Sales executive can track the performance of each product.
    • Slide bar with the date range.
    • Line chart for Amounts Disbursed by Date in order to identifying the most productive dates. 
    • Switcher for Applications and the percentage per Product. 
    • Created a summarized table Loan Level Disbursed, categorized the Amount Disbursed by 5 categories in order the Sales Executive to have a bigger picture of the amounts. 
    • Created two tables, one for the Top 10 customers Requests by PIN and one by Application ID. With this information the Sales Executive is able to identify potential customers and avoid future risks. 
This page provides deeper information regarding the products, customers, identifying areas for improvement and potential risks. 

 ## Pages 2-3: In depth analysis for the status stages.
    • Created four summarized matrix tables that allow the Sales Executive to dive deep into each customer and explore specific cases by date, product, and amount. These tables provide a detailed overview of customer transactions and help the Sales Executive identify patterns and trends that can inform strategic decision-making.
