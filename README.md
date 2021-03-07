# kickstarter-analysis

## **Overview of Project**

### Purpose

The purpose of this exercise was to see if success or failure of kickstarter campaigns for theatres and plays were dependent on their launch dates and their funding goals. 

## **Analysis and Challenges**
### Analysis of Outcomes Based on Launch Date
The analysis was done using pivot tables which are helpful to look at trends within a big data set and allows the data to be filtered easily as required. For launch dates, we looked at different theatre kickstarter campaigns and looked at the month the campaigned were launched over time and compared it to the number of plays which were successful, which failed and which were canceled. 

Resources/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals
This analysis was done using a simple summary table for plays showing the number of plays which were successful, which failed and which were canceled. This was categorized using different levels of campaigns goals. To make the summary table, we used COUNTIFS function which allows data to be selected and counted based on multiple conditions. 

### Challenges and Difficulties Encountered
I did not face any difficulty in this analysis however there can be some challenges which arise given the size of data available.  For instance, understanding which data tool will be most efficient and the way to use the tool is usually the biggest challenge. The first analysis based on month using pivot table is easy if we know how to arrange the rows by month, otherwise it can be tricky and in the past I have generally used the countif statement for this which is a longer process. 
The other challenge is to ensure the data is being counted correctly. For the second analysis, the last two goal categories given was “45,000 to 49,999” and “Greater than 50,000”. However, this misses the campaigns where goals were 50,000 and I modified the last category to include all data points. 

## **Results**
### What are two conclusions you can draw about the Outcomes based on Launch Date?
The chart shows two interesting trends which stand out. Firstly, the number of successful campaigns are much higher in the summer months (the number of cancellations remain flat throughout the year). 
Secondly, the chances of a campaign succeeding or failing/getting canceled seems equal in December – possibly the worst month to launch a campaign for theatres in the absence of other filters on this data. 

### What can you conclude about the Outcomes based on Goals?
The outcome was based on goal amount but it is not a linear relationship. Rather, smaller campaigns (<20,000) were likely to be successful. Additionally, much larger campaigns (>35,000) also had more than 50% successful plays.

### What are some limitations of this dataset?
This dataset has some limitations which should be considered when looking at the conclusions. Firstly, the dataset has more data points for US – so extrapolating conclusions for other countries should be evaluated carefully. Secondly, for the outcome discussed for plays based on goals, the data set for larger campaigns is 10 campaigns in total which is not enough to draw a concrete conclusion. This is also true for other categories as well.

### What are some other possible tables and/or graphs that we could create?
For the analysis on outcomes based on launch date, it would be interesting to dig further into the reason for higher failure rate in December. Also the length of campaigns can be included in the table to see whether that has any impact – perhaps the December campaigns are lasting longer and not able to meet their goals. We should also look at the number of backers and average donation and whether that contributes to a successful campaign. 
For the analysis based on goals, it would be interesting to see whether the same trend is true for other subcategories within theatre i.e. musical, spaces. 
