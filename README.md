# PyBer Analysis

## Overview 
The objective of this exercise is to provide insights to decision maker at PyBer. We used following two datasets to summarize insights foe ride sharing data by city type (Urban,Suburban,Rural)
 - Rides Data ( Rides details for fare and city)
 - City Data (City classification)

These datasets were combines and summarized using `pandas` package to provide comparision for ride count and fares for different city types. The results were visualized simply using `matplotlib` package. 


## Results

| City Type 	| Total Rides 	| Total Drivers 	| Total Fare 	| Average Fare per Ride 	| Average Fare per Driver 	|
|----------:	|------------:	|--------------:	|-----------:	|----------------------:	|-------------------------	|
|     Rural 	|         125 	|            78 	|  $4,327.93 	|                $34.62 	|                  $55.49 	|
|  Suburban 	|         625 	|           490 	| $19,356.33 	|                $30.97 	|                  $39.50 	|
|     Urban 	|       1,625 	|         2,405 	| $39,854.38 	|                $24.53 	|                  $16.57 	|



Based on the summarized result, following fact are revealed.

- Urban areas have shorter and frequent rides and Rural areas. ~13x more rides in urban areas than rural.
- Urban areas have more drivers that results in lower income for each driver.
-	The average fare per ride is 1.4 times less and average fare per driver is 3.4 times less in urban cities compare to rural cities indicating shorter rides and high number of drivers in urban areas.

### Weekly Revenue by City Type
![Summary_chart](/analysis/PyBer_fare_summary.png)  
The chart is showing weekly total fare revenue in different city types. 

## Summary
The results are showing that urbans have the highest number of rides and total revenue generated. However, average ride fare and driver income is lower in urban areas than suburban or rural areas. Further analysis is required based on rider wait times and duration to take necessary actions to improve business in urban areas.

### Recommendations
- Reduce driver  count in urban areas without impacting the wait times to improve average driver income.
- Minimum Ride fare can be increased to make shorter rides more profitable.
- Ride pooling could be another area to explore for business improvement
