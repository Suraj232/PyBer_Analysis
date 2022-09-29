# PyBer_Analysis
## Overview of the analysis:
The main purpose of this challenge is to analyze the ride sharing data with respect to (Urban, Suburban, and Rural)city type by using Pandas and visualizing the final data by plotting a multiple-line graph which shows the total weekly fare for each city type.
## Results
- From the summary data shown below its cleaar that Urban city type has large number of drivers as compared to other city types which adversely affect the average share per ride and average fare per driver
<img width="460" alt="Summary_Dataframe" src="https://user-images.githubusercontent.com/110261837/192930624-8bf1993c-1410-4ac3-8522-4c6bf9e72c9f.png">

- Whereas Rural city type have highest average fare per ride and average fare per driver because of least number of toal drivers available.
### Total Fare by City Type
- The above mentioned summary data was further pivoted and then grouped by weeks using resample function to get the data in terms of total fare with repect to city type.
![PyBer_fare_summary](https://user-images.githubusercontent.com/110261837/192932064-56c05554-33a0-40d7-bc46-af4b6de811fa.png)

- Highest fare earned by suburban and urban city type was during the month of February whereas for rural city type it was at the start of April.
- January was the lowest fare earned by all the city type.
- Suburban and rural city types have faced tough time during the month of March whereas urban city type had highs and lows throughout the period.
## Summary
1. The total number of drivers available has adversly affected the fare in urban city type. So Pyber should invest more in advertising so that the number of rides can be increased which will help drivers to earn more.
2. Subarban city type is performing in between the other city city types. Its more of an average performing city type, so no heavy investment is required here.
3. Rural city type has less number of rides as compared to others adn the number of drivers available is also the least. If proper investment and marketing is done to increase the total rides then this city type will prove to be very profitable for the company.
