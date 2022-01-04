# Kickstarting with Excel
An analysis of productions across various areas. Data from Module 1 for Bootcamp. 
## Overview of Project
This project was meant to provide a look into the playwriting market for Louise by providing her with insights into the performances of many different shows over a period of time. This was accomplished through the analysis of a dataset that was given to us in Microsoft Excel. 
### Purpose
This write-up is meant to provide clarity for Louise as to how she should go about funding her upcoming play, using actionaable data from the spreadsheet. 
## Analysis and Challenges
This analysis was performed first by utilizing a regular spreadsheet in Excel, and then by using Pivot Tables and Charts (as shown below) to help expound upon pre-existing data in the spreadsheet. 

Parent Category	theater			
Years	(All)			
				
Count of outcomes	Column Labels			
Row Labels	successful	failed	canceled	Grand Total
Jan	56	33	7	96
Feb	71	39	3	113
Mar	56	33	3	92
Apr	71	40	2	113
May	111	52	3	166
Jun	100	49	4	153
Jul	87	50	1	138
Aug	72	47	4	123
Sep	59	34	4	97
Oct	65	50		115
Nov	54	31	3	88
Dec	37	35	3	75
Grand Total	839	493	37	1369


 

Some challenges that I encountered included how to align my charts with the answers I was seeing in the Module, particularly the one in Deliverable 2 of the Challenge. How I overcame that challenge was to experiment with the chart options in Excel until I realized that it wasn’t in creating a new Pivot Table or Chart that I would find it but by editing the axes and labels for a regular Line graph that I would create. 
### Analysis of Outcomes Based on Launch Date
This dataset was compiled by a Pivot Table being made from the larger Kickstarter dataset, with filters being applied to only show the desired outcomes. From the Pivot Table, this data was then used to make a Pivot Line Chart that visualized the data. The data revealed that the most successful campaigns in theater happened in the month of June. 
### Analysis of Outcomes Based on Goals
This dataset was compiled simply by creating a new spreadsheet on Excel then by applying the COUNTIFS formula to figure out the Number of Successful, Failed and Canceled campaigns there were. Afterwards, the SUM formula was used to populate the Total Projects column and finally the percentage of Successful, Failed and Canceled campaigns was calculated from the past columns of Number of and Total Projects. 
### Challenges and Difficulties Encountered
A challenge that I encountered during the course of this analysis had to do with making sure that my graphs in Deliverable 2 were in line with what I was told was the correct layout in the answers. How I overcame this hurdle was through experimentation on Excel to change the Line graph to one that didn’t include certain metrics that was in the original worksheet, such as the Number of Successful, Number of Failed, and Number of Canceled campaigns. 
##  Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
One conclusion that I can make is that the most successful month to hold a campaign in Theater happens to be in May. Another conclusion I can make is that the rate of Failed projects remained fairly constant throughout the period of May-August, as the Success rate in campaigns started to sharply decline after May. This could mean that there is only a small window in which to launch a Theater campaign before the probability of success will suffer as the summer sets in.  
- What can you conclude about the Outcomes based on Goals?
The relationship between Successful and Failed campaigns seems to be inversely proportional; the higher the goal amount set for a campaign the more likely it is to fail, whereas the lower the goal amount is the more likely it is to succeed. 
- What are some limitations of this dataset?
We don’t have any information about the sentiment of the individuals donating to these projects. If we knew any feedback from the donors it could help to gauge what types of plays or productions to make in the future. 
- What are some other possible tables and/or graphs that we could create?
Theater Outcomes Based on Country of Origin. 
