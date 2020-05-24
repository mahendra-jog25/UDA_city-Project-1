# UDA_city-Projects

## Project 1

### Overview

In this project I have analysed local and global temperature data and compare the temperature trends where I live to overall global temperature trends.

### Tools Used

1.SQL- For Data Extraction. \
2.Python-For Moving Average Calculation and Visualization.

### Extracting Data

Following SQL query was executed to retrieve data mention below:

SELECT * FROM city_list \
WHERE city LIKE 'Pu%' AND country LIKE 'Ind%';

SELECT * From city_data \
WHERE city Like 'Pu%' AND country LIKE 'Ind%';

SELECT * FROM global_data;

1.Local Dataset-Pune(India) \
2.Global Dataset

### Calculation
Using pandas rolling function moving average was calculated for 5 years and 10 years.

### Observations:
1. Global and Local temperatures seems to rising (increase in trend) as years are passing (over a decades), 
2. Strong correlation can be seen between rise in temperature globally as well as locally.
3. Global average temperatures are 17 times much cooler than local average temperatures.
4. Based on correlation values average local temperature can be estimated by average global temperature.
