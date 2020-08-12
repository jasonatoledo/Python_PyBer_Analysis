# Python_PyBer_Analysis

## Overview

The purpose of the new analysis was to get a summary analysis of the different city types, the average fare per ride & driver, and total fares. From here, I transformed the dataframe into a new dataframe that contained the sum of fares by city type and date, which was filtered to a specific date range of January through April, then resampled to convert the daily dates into weekly dates by city type.

## Results

As seen from the numbers and the line chart, the total amount of fares collected was greatest in the Urban city type. The cost per ride was highest in the Rural city type. Although the cost per ride was lowest in the Urban type vs the highest in the rural type. It seems to follow the basic principles of supply and demand, where Urban has the most ride reqeusts, most drivers, and the lowest average cost per fare but also takes in the most revenue based on the volume of rides. The opposite happens in the Rural type, while Suburban is in between Urban and Rural types.

https://github.com/jasonatoledo/Python_PyBer_Analysis/blob/master/Resources/Multi%20Line%20Chart.png

This is what the summary dataframe looked like per city type for total rides, drivers, fars, average fare per ride, and average fare per driver:

https://github.com/jasonatoledo/Python_PyBer_Analysis/blob/master/Resources/PyBer%20Summary.png

## Summary

Three proposed business recommendations based on addressing the disparities between city types:

1) Promote driver acquisition in the rural segment to increase the number of drivers per capita. In addition, perhaps create promotional campaigns to increase ridership and therefore average fares may possibly reduce.

2) Introduce a frequent rider program to reward users who use the ride share service enough to gain rewards and possibly increase the activity in the Rural and Suburban city types.

3) Offer promotional coupons or discounts during the weeks that showed a dip in fare activity to increase year over year ridership.
