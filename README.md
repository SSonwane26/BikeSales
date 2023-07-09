# Bike Sales

## Europe Bike Store Sales
About Business
At Bike Store, we’ve realized our vision of creating a bike platform that serves cyclists all across Europe. With us, you’re able to order bicycles , cycling clothing and accessories directly to your door. Our extensive range can be browsed wherever you are and at any time. Basically it sale product, both online, and offline, in Europe as well as outside from Europe.
## About Project
Data set from [KAGGLE](https://www.kaggle.com/datasets/prepinstaprime/europe-bike-store-sales)
We are going to analyze the bike sales form countries like Australia, Canada, France, Germany, United Kingdom and United States.
We are using Power BI Desktop for our analysis and for making of reports and dashboards, using charts and graphs.
This dataset contains information about  bikes sales, clothing sales and accessories sales. The dataset includes various features of the sales such as Order Date, Customer Age, Customer Gender, Location of Order, Product Information, Order Quantity, Cost of Product, and Price of Product.
## Steps
### Power Query
- Load csv file to Power Query Editor.
- As dataset is clean so skip Data Cleaning process.
- Split Date Column into Day, Month and Year Columns.
- Add Conditional Column for grouping the Age of customers like Youth(<25), Young Adults(25-34), Adults(35-64), and Seniors(>64).
- Add Custom Columns like Cost (order quantity * unit cost), Revenue(order quantity * unit price), and Profit(Revenue - Cost) .
### DAX Functions
- Total Revenue = SUM(EuropeBikes[Revenue])
- Total Product Sold = SUM(EuropeBikes[order_quantity])
- Total Profit = SUM(EuropeBikes[Profit])
### Data Visualizations
- Create KPIs, Total Product Sold, Total Revenue, Total Profit, and Return on Investment %.
- Create Bar Charts for Top Country by Revenue, and by Product Category Sold, Top Sub Category by Sales, Top State and Bottom State by Sales, Sales and Revenue by Age Groups.
- Create Trending Analysis using Column Chart Monthly Trend and Line Chart for Annual Trend.
- Create Tree Map for Sales and Revenue for Sub Category
- Create Bubble Chart for Total Journey of Profit and Sales form 2011 to 2016 
## Conclusion:
- Total Product Sold 1.35M.
- Total Revenue Total Profit are 95.18M Euros and 42.13M Euros.
- Top 3 Countries in term of Revenue are United States, Australia and United Kingdom.
- Top 3 Countries in term of Product Sold are United States, Australia and Canada.
- Most Revenue are generated form Adults. 
