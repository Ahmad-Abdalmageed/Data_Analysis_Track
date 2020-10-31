# Weather Trends Exploration 

This is a simplified exploration of Weather Trends Dataset, Investigating the Temperatures in city for a number of years Vs the global trend for that year. Since i live in Egypt i will be choosing cities like Cairo. So lets start our Exploration.
    
### Content
1. Introduction 
2. Loading the Dataset 
3. Visualizations 
4. Conclusions

## Introduction 

The Dataset is provided on a workspace in Udacity\`s Data Analysis Nano Degree, i extracted the dataset using sql, extracting only data relevant to the cities we proposed (Cairo) and it\`s average temperature per year and the global average temperature that year. The database consists of 3 tables.
* city_list - This contains a list of cities and countries in the database. Look through them in order to find the city nearest to you.

    `city_data : year, city, country, avg_temp`
* city_data - This contains the average temperatures for each city by year (ºC).

    `city_list : city, country`
* global_data - This contains the average global temperatures by year (ºC).

    `global_data : avg_temp, year`
#### SQL Code 
  `SELECT city, city_data.avg_temp AS city_temp, global_data.avg_temp AS global_temp, city_data.year
    FROM city_data
    JOIN global_data
    ON city_data.year = global_data.year
    WHERE city_data.city = 'Cairo';
`