# PyBer_Analysis
## Overview of the Analysis
The purpose of this challenge was to create a ride-sharing summary DataFrame by city type, and a multi-line chart of total fares by city type. 
### Deliverable 1: Ride-sharing summary DataFrame by city type:
In order to create this DataFrame I had to create multiple data series using city type as the index to find the total rides for each city type, total drivers, total fare amounts, and average fare per ride.  To find the total rides for each city type I applied the count() method to the "ride_id" column.  To find the total drivers and total fare amounts I applied the sum() method to the "driver_count" and "fare" columns.  To find the average fare per ride I applied the mean() method to the "fare" column. I then calculate the average fare per driver by city type by dividing total_fares_by_city by total_drivers_by_city_type.  Then I created the summary DataFrame pyber_summary_df by adding each of those data series to the new DataFrame.  Using code already given in the starter code, the index name was deleted. Lastly, I formatted the columns to use commas for values over 1,000 and to add a dollar sign and 2 decimal point format for dollar amounts.
### Deliverable 2: Create a multiple line plot chart of total fares by city type. 
## Results

## Summary
