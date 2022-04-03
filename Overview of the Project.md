Overview of the Project: 

The purpose of this project was to test our knowledge of what we learned in the excel modules. For this challenge there are two main objectives. One is to create an analysis based on goals, and the other one based on launch date. A specific data set was given as a basis to find these two objectives. The data set itself, was based on an individual’s desire to fund as much money for their play in a short amount of time.  

Analysis and Challenges:

Analysis of Outcomes Based on launch Date: For analysis one the main objective was to figure out the outcomes based on the launch date data. Here we had to exercise our knowledge of graphing and pivot tables in Excel. To visualize the campaign outcomes based on their launch date. To specify which ones were, successful, failed or canceled. Given that a lot of the material had been a review, it was not hard to create, filer, and define new cells based on what we wanted. 

Problems encountered: 

There were a few problems that were encountered. Especially when trying to filter the pivot table, to match the what the chart should have look like. While not hard, (Data tab, filer, then the little drop-down arrow in the cells).  For some reason it was slightly off. Having to add a month column to filter the chart correctly. Which made the line graph correct, per-say? But just slightly off. Meaning the total successful, failed, and canceled are correct. However, with-in each of the months the numbers are slightly off…But the grand total of what could have possibly happened, was that one of my main table filers was not filtered correctly. 

![](Aspose.Words.d9cc461e-81b8-4f0c-a0b3-f9b3a37d2793.001.png)

![Graphical user interface, application

Description automatically generated](Aspose.Words.d9cc461e-81b8-4f0c-a0b3-f9b3a37d2793.002.png)

![Graphical user interface, table

Description automatically generated](Aspose.Words.d9cc461e-81b8-4f0c-a0b3-f9b3a37d2793.003.png)


Analysis of Outcomes based on goals: 

For this assignment, the main objectives were to visualize the percentage of what plays were successful, failed, or canceled based on the funding goal amount. To begin we needed to create a new chart to hold all the data. That chart had to consists of eight columns of goal, # successful, # failed, # canceled, total projects, precent of success, percentage of failed, precent of canceled.  With a specific range in the goal column of 1000 or less, 1000 to 4999, 5000 to 9999, 10000 to 14999, 15000 to 19999, 20000 to 24999, 25000 to 29999, 30000 to 34999, 35000 to 39999, 40000 to 44999, 45000 to 49999, and 50000 or more. To get these specific data sets, one had to filter out the main data set, and use the COUNTIFS() fxn to get these ranges. 

For example: This one was used to find out which ones had a $1000 dollar or less.

![](Aspose.Words.d9cc461e-81b8-4f0c-a0b3-f9b3a37d2793.004.png)

=COUNTIFS(KickStarter\_Challenge!$D:$D,"<1000",KickStarter\_Challenge!$F:$F,"successful",KickStarter\_Challenge!$X:$X,"plays")

While this one below was used to create the dollar, amount ranges. Do note that each dollar range had to be changed but the formula stayed the same. 

![](Aspose.Words.d9cc461e-81b8-4f0c-a0b3-f9b3a37d2793.005.png)

=COUNTIFS(KickStarter\_Challenge!$D:$D,">=1000",KickStarter\_Challenge!$F:$F,"successful",KickStarter\_Challenge!$D:$D,"<=4999",KickStarter\_Challenge!$X:$X,"plays")

From there, all one had to do was use the SUM() function to calculate the total amount of projects. Meaning, it should have looked like Sum(B2:D2) and you did that for all the cells 2-13 to get the total amount of projects. Next, we had to find the precent of successful, failed, and canceled. To do this, used the function of Sum(E2/D2) then filter the format to percentage. Then do this for the rest of the cells. Which is essentially is the same process used to tabulate them all to give the precent. But note because there were no canceled projects specifically for plays it will show 0. Once that was competed, a pivot chart based on the fully populated data set needed to be made. The instruction wanted the x-axis to have the goal amount. Which would have been the goal ranges that were made. Then, the axis was to be populated as the precent of Successful, failed, or canceled. 

Challenges and difficulties Encountered: 

There was quite a few things that got overlooked. Especially when using the COUNTIFS() function. The thing was the formulas was correct. But one of the filters was wrong. Which happened to be the subcategory “plays” not being accounted for. Which kept leading to the wrong data…which led to the wrong pivot chart.  Which lead to the making of an entire new excel based on goals that specifically had successful, failed, and canceled.  But once again the COUNTIFS() functions formula was correct. However, “plays” were not being accounted for, and therefore was sill incorrect. However, once “plays” were accounted for. The correct number of Successful, failed, and canceled were displayed, and populated correctly in both the data set and pivot table. Now the only other thing that was odd, was in the pivot chart goal range (5000 to 9999). For some reason, it decided it want to be at the end near (50000 or more) and it’s not cooperating on going back to the correct numerical range.   


Results:

#Some conclusions that one could draw from the Outcomes based on Launch date. Is that Months: June (6), July, (7), and August (8) had the highest success rate.  While months February (2), and December (12), Had the lowest success rate. 

The conclusions that one can draw from the outcomes based on goals. Is that there were not any cancelations. But a specific project failed to meet the minimum goal, that was trying to be attained. Furthermore, when the compared to the total projects there was only one goal range that failed to meet the minimum goal which happened to the 45000-44999.

Some limitations of this data set could be the filtering itself. While it is helpful to have large amounts of data. When filtering those individually, it can become challenge to describe what those specific sets are being interpreted as. Especially if it does not get account for in one of the functions. It therefore can skew the entire data set of what on is trying to do. But that being said, it’s a simple yet time consuming fix. 

Other possible tables/graphs that we could create could possibly be: outcomes based on currency, and country, and how they compare. Or see what was successful based on a specific year launched. Or what subcategory took up most of the budget. Just to name a few. 

