# RareBurger-Dashboard
In this project, restaurant KPI data was analyzed to gain insights and make comparisons to peer restaurant performance. The restaurant of interest was The Rare Burger. KPIs included sales, number of customers, customer spend by location, online spend per location, and median spend per transaction. Two sources were required to access the data, a local csv file with The Rare Burger data as well as a data from the Snowflake Marketplace containing New York City Restaurant data. 

Firts, SQL queries were used to set up the tables. Second the Schemas were created, then the databases and warehouses configured in Snowflake. Next, SQL queries were used to narrow the desired data and load the tables. As our data was spread across two sources, a joining query was required. 
***

Using SQL Query to join data tables limiting to one dependent outcome (Raw Number of Customers)
<image src="/Resources/joining_tables.png">

  
* * * *


Next, the charts were configured to display the data. In this case horizontal stacked bar chart was used for the Raw Number of Customers by zip code.
<image src="/Resources/first_tile_dashboard.png">

* * * *


Final Dashboard after creating other tiles to display additional outcomes
<image src="/Resources/final_dashboard.png">


  
  ### Summary
