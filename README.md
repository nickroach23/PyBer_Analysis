# PyBer_Analysis
### OverView of the Analysis
I created a analysis and a visualization of the ride-sharing data. I had two datasets; ride data with the location, date and the fare for every ride, and also the city data describing the type of city and number of drivers. The goal was to compare the fare of riders in each city type: urban, suburban and also rural. I creates a visualization with the matplotlib library to give some recommendation to the CEO addressing any issues given to the city types. 

Throughout this analysis I used the Jupyter Notebook, pandas and also the matplotlib.

### Results
In order to perform this analysis, I had to merge datasets using left join based on the city column and was able to get one dataset. I created a summary dataframe by the city type. It was shown that there are few drivers and rides in the rural city that has a higher average fare comapred to the urban cities. 

* The average fare per ride is around 1.5 times less and the average fare per driver is 3.5 times less in the urban cities compared to the rural cities ($24.54 vs $34.62 and $16.57 vs $55.49)
* The total fares in the urban cities is higher than the rural cities and about 2 times higher than the suburbs ($39,854.34 vs $4,327.93)
![Screenshot (44)](https://user-images.githubusercontent.com/64110317/128644793-6bca5db0-d563-480d-98f0-d28dc8fd3439.png)

For a better visualization I created a multi line plot to show the total weekely fares for each of the city types. Yellow representing the urban cities is higher than red and blue which represents the suburban and rural city. Comparing that the has more total fares in the urban cities compared to the ones in the suburbs and rural cities. 
![Screenshot (46)](https://user-images.githubusercontent.com/64110317/128645057-4cccb4c1-ec86-41c3-9e87-1f710bcc3fb6.png)


### Summary

I would focus on improving the profits of the urban cities. Reason why is yes the urban cities does make more in revenue but the rural cities are having a higher impact on the profits. I would also add by trying to lowering the number of drivers in the urban cities. There's almost as twice of drivers than there are rides (2,405 drivers vs 1625 rides), meaning drivers are only given a most one ride. 

