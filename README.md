# UDA_city-Projects

## Project 1

### Overview

In this project I have analysed local and global temperature data and compare the temperature trends where I live to overall global temperature trends.

### Tools Used

1.SQL- For Data Extraction.
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

