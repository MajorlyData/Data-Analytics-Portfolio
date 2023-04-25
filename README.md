# Data Analytics Portfolio - SQL

Welcome to my SQL Portfolio! This code repository contains examples of SQL I've written that showcases a variety of use cases and real world examples. Feel free to take a look around and reach out via email if you have any questions: majorlydata@gmail.com

## Highlighted Projects

+ **[Customer & Order Analytics](https://github.com/MajorlyData/SQL/blob/main/Customer%20%26%20Order%20Analytics):** For this project, I queried multiple instances of data from a database named Sales_DB to highlight a variety of real world observations, including showing the number of orders for a specific month, the types of orders placed and the amount of revenue made. I also utilized important SQL functions to answer vital questions about the data, such as using JOINs to connect two tables and extract overlapping information, using subqueries to check if values match each other and making use of aggregate functions to evaluate different points of interest, such as SUM and COUNT. Lastly, and importantly, I employed data cleanup to make sure the data I did extrapolate was correct and in good standing, specifically to filter out any orderID or Product that may have been entered incorrectly or have become corrupted by external factors.
+ **[Bike Lane Analytics](https://github.com/MajorlyData/SQL/blob/main/Bike%20Lane%20Analytics):** In this project, I used SQL to query and analyze a table containing information about bike lanes around a city. The table included information such as each lane's street name, safety rating and the year it was installed. Making use of vital SQL functions such as CTEs and Window Functions, including 'partition by' and 'rank()', I discovered valuable insights into each bike lane and its standing within the recommendations of the city. For example, I first gathered each bike lane's average safety rating, as each one has two separate ratings. Using that value, I employed the 'partition by' clause to show each lane's average safety rating while still displaying each bike lane separately. Finally, I used a 'case' statement to gauge whether each bike lane was good, bad or needed to be improved, thus creating a resulting table that can easily be understood and read over efficiently.
