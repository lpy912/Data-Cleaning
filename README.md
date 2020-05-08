# Data-Cleaning
This repository is related to House Price Prediction project where I demonstrate how to clean scrapped data using Python Pandas. It is also part of our online learning assessment.


Before we start, we need to identify the scope of data cleaning by screening through the data.
In summary, we have 10 items to be completed in this data cleaning exercise.
1. Area-To strip the blank space in front of the values
2. To delete unused columns in analysis such as index column and link used in data scraping
3. Price-eliminate "RM" (currency name) and change the data type to numeric
4. Bedroom-eliminate "Bedroom" and replace all blank with NA
5. Other Info-replace all blank with NA then change column name to entitelment
6. Carpark-replace all blank with NA and ensure the data type is numeric
7. Square Feet- convert all values in Acres to square feet to ensure the same Unit of Measurement is used
8. Square Feet-strip "sq ft" from the values
9. Facilities-replace blank with NA
10. Facilities-split the values using comma to ensure one column only has one facility
