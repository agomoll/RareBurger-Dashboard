# RareBurger-Dashboard
Snowflake was used to analyze restaurant KPI data to gain insights and make comparisons with peer restaurant performance. The restaurant of interest was The Rare Burger. KPIs included sales, number of customers, customer spend by location, online spend per location, and median spend per transaction. Two sources were required to access the data, a local csv file with The Rare Burger data as well as a data from the Snowflake Marketplace containing New York City Restaurant data. 

Firts, SQL queries were used to set up the tables. Second the Schemas were created, then the databases and warehouses configured in Snowflake. Next, SQL queries were used to narrow the desired data and load the tables. As our data was spread across two sources, a joining query was required. Also, the restaurant results were filtered to return only those businesses focused on burgers.
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
  * Top perfoming zip codes for all burger focused restaurants include 10036, 10019, and 10003.
  * In the top performing zip code (10036), The Rare Burger led in terms of customers per location (1,440) followed by Hard Rock Cafe (329), and The Perfect Pint(175).
  * For zip code 10036, median spend for customers by trasaction was highest for the Burger and Lobster restaurant ($168.28), lowest for Whitman's ($47.04) and was on average $89.83. The Rare Burger median spend was $111.19. By comparison, the median for zip code 10019 was $392.24.
  
#### Suggestions
  * Investigate pricing accross restaurants to optimize The Rare Burger pricing strategy. 
  * Investigate pricing and puchase order details across zipcodes to look for oportunities for standardizing or optimizing. 
