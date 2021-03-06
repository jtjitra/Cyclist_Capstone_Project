# Cyclist_Capstone_Project

In this project, I played as a Junior Data Analyst helping Cyclist, a bike-share company, analyze its rider data to determine how to convert casual riders into members. In order to do this, I needed to understand how casual riders and member riders use Cyclist bikes differently. 

## Method 
The biker data was downloaded from an Amazon drive in .csv files. One .csv file contained one month of biker data so I downloaded all the data from January 2021 to January 2022. All the files together amounted to 1062.9 MB or 1.06 GB. Excel kept crashing whenever I tried to open the files so I decided to process and prepare the data using R since it can handle large amounts of data. If you'd like to view my R code, you can click the file labelled 'Cyclist_Capstone_Project.Rmd'.

# Analysis 
Here are the visuals I created for data insights using R.

![Number of Rides per Day of the Week](https://user-images.githubusercontent.com/100651280/158280301-14d932cd-4c48-41ec-b110-5252e136c919.png)

This bar chart shows the number of rides per day of the week for each biker type: casual riders and member riders. From the graph, we can see that members go on the most bike rides during the weekdays. However, during the weekends, we can see that casual riders go on the most bike rides. 


![Average Duration of Rides per Day of the Week](https://user-images.githubusercontent.com/100651280/157992176-b382cbb7-25d6-4045-b357-01d8d226c147.png)

This bar chart shows the average duration of rides per day of the week for each biker type. This visualization helps us see how long each biker type spends on their bike ride. We can see that casual riders go on longer bike rides than members on every day of the week.


![Rides per Month (2021)](https://user-images.githubusercontent.com/100651280/158280457-6200417f-3680-4199-9cf8-d579451d6b5c.png)

This bar chart shows the total amount of rides per month of the year 2021 for each biker type. This visualization shows the months labelled as numbers. We can see that casual riders ride more during month 7-8, which is the month of July-August.


![Usage of Different Ride Types](https://user-images.githubusercontent.com/100651280/158280353-a78268a4-2777-4409-b503-d10b2142cd7b.png)

This bar chart shows the usage of different ride types by number of rides for each biker type. This visualization helps us identify which type of bike each rider uses the most. Casual riders use docked bikes more than members. Meanwhile, members use classic and electric bikes more than casual riders. 

# Recommendations
As seen from the bar charts, casual members tend to:
* bike more on the weekends
* go on longer bike rides
* bike more on the month of July-August
* bike more on docked bikes

In order to convert more casual riders to members, Cyclists should:
* offer special promotions and/or discounts on the weekends
* offer special promotions and/or discounts for longer bike rides
* do special promotions for the month of July-August
* offer special promotions and/or discounts for docked bikes 
