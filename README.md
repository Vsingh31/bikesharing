# Bikesharing
## Overview of the analysis
The purpose of the Bikesharing analysis is analyze the NYC bike-sharing data and using Tableau to visualize bike-sharing data also to convince investors that a bike-sharing program in **"Des Moines"** is a solid business proposal. To solidify the proposal,I will do bike trip analysis with the NYC bikesharing data and using tableau to visualize my analysis and make story to present to skateholder or investores to covince them for business proposal.I will create a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* how the number of bike trips for each type of user and gender for each day of the week.
 
 

[link to Dashboard](https://public.tableau.com/app/profile/vandana6207/viz/Book6_16390632309370/NYCCitiBike)

### Results: 
1)how many bike trips were recorded during the month of August.August have good weather for renting the bicycle.so we will find out the no of tips were recorded during the month of august.so no of trips are 2,344,244 in August .

2)What Is the Proportion of Short-Term Customers to Annual Subscribers? To get this answer when we see the data,there is one column usertype is available,with the help of this column we can understand that bike-sharing service have two type of customers. One who is annual subscribers and other are short-term customers.so for visualizing the data proportion we will use pie chart.

3)Find the Peak Riding Hours in August.For finding this we will see our starttime column that given in year,teableau have option to change year into hour. so we will change start time in hourly in dimention and take sum of all record as measure and make bar chart to visualize the peak riding hour in august.

4)What Are the Top Start Bike Stations and top End Bike Stations in the City for Starting and ending a Journey? For this,we need the latitute and longitute of the location from where bike stations are located in the city. In our dataset,start station latitude and longitude and end stations latitude and longitude are available. And I need also count of all records to know that top start and end bike stations.we can use size and color according to no of records,means where no of records is more, the size of bubble will big and color of bubble will also dark.
5)What Is the Gender Breakdown of Active Riders? Before starting any business we will figure out first who will be our potential customers,for this we will analyse the gender breakdown to know who will be use our bike most.For this, Gender column is available in my dataset,but the values are given as 0,1 and 2.but we can not label our data as 0,1 and 2 to show our investors. So we will change the values 0 for unknown,1 for women and 2 for men by writing a if else code in calculated field of gender and make a new column and then malke visualization from that.For visualization of this we will use pie chart.
6)Find the Average Trip Duration by Age.for this,we will take the birthdate of customers in measure and avg of trip duration in dimention to visualize the avg trip duration by age.
7)Show the length of time that bikes are checked out for all riders and genders.

![checkout timeby](https://user-images.githubusercontent.com/90277142/146656598-3dbbcb53-ce67-4d69-aba9-3f5a700bb2ca.png)







Summary: Provide a high-level summary of the results and two additional visualizations  are suggested for future analysis (5 pt) that you would perform with the given dataset.


