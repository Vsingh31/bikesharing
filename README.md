# Bikesharing
## Overview of the analysis
The purpose of the Bikesharing analysis is analyze the NYC bike-sharing data and using Tableau to visualize bike-sharing data also to convince investors that a bike-sharing program in **"Des Moines"** is a solid business proposal. To solidify the proposal,I will do bike trip analysis with the NYC bikesharing data and using tableau to visualize my analysis and make story to present to skateholder or investores to covince them for business proposal.I will create a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* how the number of bike trips for each type of user and gender for each day of the week.
 
 My Tableau story for NYC bike-sharing,[you can see here](https://public.tableau.com/app/profile/vandana6207/viz/Challenge_16394980346660/Story1?publish=yes).



### Results: 
1)**How many bike trips were recorded during the month of August.** August have good weather for renting the bicycle.so we will find out the no of tips were recorded during the month of august.so no of trips are 2,344,244 in August .
* **What Is the Proportion of Short-Term Customers to Annual Subscribers?** To get this answer when we see the data,there is one column usertype is available,with the help of this column we can understand that bike-sharing service have two type of customers. One who is annual subscribers and other are short-term customers.so for visualizing the data proportion we will use pie chart.
* **What Is the Gender Breakdown of Active Riders?** Before starting any business we will figure out first who will be our potential customers,for this we will analyse the gender breakdown to know who will be use our bike most.For this, Gender column is available in my dataset,but the values are given as 0,1 and 2.but we can not label our data as 0,1 and 2 to show our investors. So we will change the values 0 for unknown,1 for women and 2 for men by writing a if else code in calculated field of gender and make a new column and then malke visualization from that.For visualization of this we will use pie chart.
            
![noofridesbyuserand_gendertype](https://user-images.githubusercontent.com/90277142/146662019-21423862-7ffa-40d0-bdae-e0b185bf1704.png)
            

2)**Find the Peak Riding Hours in August.** For finding this we will see our starttime column that given in year,teableau have option to change year into hour. so we will change start time in hourly in dimention and take sum of all record as measure and make bar chart to visualize the peak riding hour in august.

![peakriding_hours](https://user-images.githubusercontent.com/90277142/146662549-65f4f63a-033d-47cf-a573-137ac8a9da75.png)


3)**What Are the Top Start Bike Stations and top End Bike Stations in the City for Starting and ending a Journey?** For this,we need the latitute and longitute of the location from where bike stations are located in the city. In our dataset,start station latitude and longitude and end stations latitude and longitude are available. And I need also count of all records to know that top start and end bike stations.we can use size and color according to no of records,means where no of records is more, the size of bubble will big and color of bubble will also dark.

![topstarnendlocation_bycount](https://user-images.githubusercontent.com/90277142/146662386-e1e04720-a013-46c9-a115-c14624da75a7.png)


4)**Find the Average Trip Duration by Age.** for this,we will take the birthdate of customers in measure and avg of trip duration in dimention to visualize the avg trip duration by age.

![avgtrpduration_byage](https://user-images.githubusercontent.com/90277142/146662210-443ac515-ff1f-43ff-b65f-46de5f62a43b.png)


5)Show the length of time that bikes are checked out for all riders and genders.
* This graphing of number of trips by duration show that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.
* This breakdown of number of rides by duration, separated by gender, makes it even more apparent how many more rides are taken by male-identifying customers.

![checkout timeby](https://user-images.githubusercontent.com/90277142/146656598-3dbbcb53-ce67-4d69-aba9-3f5a700bb2ca.png)

6)Show the number of bike trips for all riders and genders for each hour of each day of the week
* A heatmap also helps show weekly usage patterns. Once again we can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours, every day of the week.

![tripsbyweekend](https://user-images.githubusercontent.com/90277142/146661429-2a117a57-99e8-4d39-aec8-3c8fd819b547.png)

7)how the number of bike trips for each type of user and gender for each day of the week.
Lastly, this heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.

![usrgenderweekday](https://user-images.githubusercontent.com/90277142/146661570-f5103d18-e166-4483-bdb4-aec9901ba4c6.png)


#### Summary:
In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

1)The Top Starting Locations by Gender breakdown,so we can see that which starting point have majority of male or female or unknown.so we can Analyse further and take decision to increase our business.

![Topstartbygender](https://user-images.githubusercontent.com/90277142/146701349-b539b5ed-e210-4a3d-9b49-4833cc1d48ff.png)

2)The Top Ending Locations by Gender breakdown,so we can see that which ending point have majority of male or female or unknown.so we can Analyse further and take decision to increase our business on which Locations. According to analysis and visualization, We can give some offer according to gender,so our customer will love our services.

![Topendbygender](https://user-images.githubusercontent.com/90277142/146701360-db27ce6c-8d12-4c4e-a01d-a34936b94631.png)



