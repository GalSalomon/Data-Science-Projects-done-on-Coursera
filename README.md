# Data Analysis and Visualization in Python

## 1. [Comparison of House Prices before and after a recession](https://github.com/SphericalCopper/Data-Science-Projects-done-on-Coursera/blob/master/Module%201%20Assignment%204.ipynb)

Pandas library was used to appropriately sort through house data in the United States, and then after achieving the intended changes, a t-test was performed on the data to compare the ratio of the mean price of houses in university towns the quarter before the recession starts, compared against the quarter representing the recession bottom.

- Split months of the years into quarters, and used these quarters to determine when recessions, and recession bottoms were.
- Modified dataframe to return information on University towns. 
- Used  `ttest_ind` from `scipy.stats` library to conduct [t-test](https://www.investopedia.com/terms/t/t-test.asp) to conclude that University towns have their mean housing prices less effected by recessions..

## 2. [Tracking Record high and low temperatures over 10 years](https://github.com/SphericalCopper/Data-Science-Projects-done-on-Coursera/blob/master/Module%202%20Assignment%202.ipynb)

In this assignment, data on temperature was used to create a visualization of record high temperatures in the area of Ann Arbor, Michigan. Points at which the previous temperature record were exceeded are also denoted. The nature of what this graph tracks is useful for keeping track of changes in typical climate behaviors. 

- Used `matplotlib.dates` from `matplotlib` library to assist in plotting timeframe of days (to represent daily temperature records), using the figure of months on the x-axis.

![Temperature records](https://i.gyazo.com/f14765ba8f355917db82dfba917c000f.png)

- The line bars above represent the highest and lowest record temperatures set each day between the years 2005 to 2014. 
- The points on the bar represent a temperature record (for either high or low temperature), in which the temperature observed in 2015 broke the record high or low temperature in the preceeding 10 years.
- Notice that **during the months of February, a new low temperature record was set almost daily**, and by a significant margin of 5-15 degrees celcius! 
- Likewise, **in December, temperature records in 2015 very frequently broke those set in 2005-2014** by margins of around 5 degrees celcius on average.
- A graph of this nature which tracks temperature records being broken is very helpful for tracking crucial changes in the climate.

## 3. [Creating a Custom Visualization](https://github.com/SphericalCopper/Data-Science-Projects-done-on-Coursera/blob/master/Module%202%20Assignment%203.ipynb)

Randomly generated numbers into a dataframe are plotted and visualized in the form of a bar chart. A point of interest on the y-axis is identified, and colours are also used to help convey how much further the bar graph value is from the y-axis value of interest.

## 4. [Link between Household income and sports participation in Singapore](https://github.com/SphericalCopper/Data-Science-Projects-done-on-Coursera/blob/master/Module%202%20Assignment%204.ipynb)

Data was acquired on 1) [Weekly Sports participation](https://www.msf.gov.sg/research-and-data/Research-and-Statistics/PublishingImages), and 2) Yearly income of families. A correlation between these two factors was thus visualized, observing that an increase in financial stability corresponded to an increase in leisurely activities (of which sports is one).
