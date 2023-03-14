# Module_18
# CitiBike Analysis

Link to the Tableau Project here:

https://public.tableau.com/app/profile/siobhan1460/viz/CitiBike_16786699583590/CitibikeStory 

# Project Scope


Background
Citi-Bikes
Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

Analysis of Tableau Worksheet:

I decided to use the CSV's covering June 2020 - November 2020 to compare seasonal data with a large enough dataset. I used Jupyter notebook to combine the CSV's (Notebook attached for reference)

Once this was combined I then went to analyse the data in Tableau, creating calculated fields for the areas I wanted to analyse (Season, Age, Weekend/Weekday)

Top Data Findings from the Tableau Notebook:

1. The starting stations and area locations.

https://github.com/SBrindley/citi-bike/blob/main/Citibike%20Story%20Gender.png?raw=true

The Visualisation shows the starting station using colours and sizes of the markers to display the popularity (legend on top right).
You can filter the data furhter using the dropdown for month and also sue the text box to type a station to see the location and usage data on the map.
The top 10 starting locations are all based in the Manhattan Area, meaning this is the most popular area to start a bike journey. The bottom 10 starting stations are all based near the Bronx and out of the city. 

2. Age and Gender usage



The gender charst show 57.89% of users are male indicating a big majority with 12.34% being unknown and 29.78% being female. Looking at the monthly trips broken down by gender, the Male riders tend to have an upwards usage from June to October with a sharp fall in November due to the winter months. The female and unknown riders look to be the opposite with a downwards trendline for the same period of time. 
Looking at ages for the riders, we can see a lot of false data has been inputted with some users recording birth dates in 1876 and a huge spike in users recording birthdates in 1969. This could be down to users maybe having a default value of 1969 when slecting their birth date and not altering, as the huge spike is caused by the customers recording this birth year and not subscribers who seem to have more accurate information. when we disreagrd the huge spike for 1969, the most common age range of users is between 25 and 33. To get a more accurate representaion, I would suggest the allowed birthdates be shortened form 1900 onwards and there being no default birth date value.

3. Usage stats between Subscribers and Customers

https://github.com/SBrindley/citi-bike/blob/main/Citibike%20Story%20Usage.png

The graphs can be filtered using the graphs or the right hand legend for users to see the statistics for usage between users and subscribers. Subsribers are much higher users of the citibikes than the general customer type. When we look at the graps we can see a pattern of customer usage being much higher on a Saturday and Sunday than midweek, but the subscriber usage being more levelled out when comparing the same days. We can also see looking at the weekday vs weekend usage graph that Subscriber usage midweek is much higher at the commuting hours than the same time at the weekend showing subscribers tend to use the bikes for commuting. However, when we look at the customers this is not as defined with the graphs for commute times only very slightly raising midweek showing a tendency to not as be heavily relied upon as the subscribers for the commute journey.

4. Seasonal Usage

Bike usage is the greatest in September as indicated in the circle chart above. In the bubble chart we can see a pattern with more the usage being steady for both seasons, females and unknown genders using the bikes more in the Summer but Males using the bikes more than they do in the Summer. We also see a bigger share of Subscribers using the bikes in the Autumn which would indicate more casual users using the bikes in the nicer Summer months.


