# NYC CitiBike Bikesharing

## Project Overview
This analysis of CitiBike's bikesharing program in NYC is provided as research for a similar program in Des Moines, Iowa, and aims to determine the feasibility of such a business. Looking at data on numbers of bikes, numbers of trips, peak times of travel, types of customers, trip duration, and bike use/lifecycle will be useful in comparing the potential population needs of another program in another city and perhaps identify potential differences in customer use as well as highlight budget requirements.

The inspiration for this business proposal is based on the personal experience of the presenters, who feel their most recent trip to NYC was highly enhanced by the bikesharing business there.

## Resources

Data Source: 201908-citibike-tripdata, dateformat-citibike-tripdata

Software: Jupyter Notebook, Tableau

## Analysis and Results of Data
The number of total trips included in the dataset used for this analysis is 2,344,224 trips. All trips took place in 2019. CitiBike users have the option to be "subscribers" or anonymous users. Gender appears to have been known for all subscribers and bikesharing use specific to gender was therefore also analyzed.

The line chart below shows frequency of trip durations for all trips in the dataset (2,344,224 records). Trip duration peaks in frequency at 5 minutes and then drops off steeply with very few trips longer than 45 minutes. 
![Users Checkout Time](https://user-images.githubusercontent.com/108022219/193721468-528b89f4-653b-46d8-a6ed-65d8b9123a91.png)

This next line chart shows trip duration frequency separated by gender. Female and unknown-gendered riders account for roughly one third of the rides while male riders account for two thirds. Trip durations appear to be similar no matter the gender of the user or the far more frequent use of the CitiBike bikesharing service by males.
![Checkout by Gender](https://user-images.githubusercontent.com/108022219/193721605-232acbe0-1045-4bde-83f3-e564b731def9.png)

This next figure below separates peak service times by user, by gender. Again use seems to be consistent among genders with male users having more frequency.
![Gender Weekday Per Hour](https://user-images.githubusercontent.com/108022219/193721607-45c10345-fb07-49ca-86f4-1e02351a5fe5.png)

The next chart below successfully visualizes type of user (subscriber or occasional), gender of user, time used, and frequency of use. This visualization appears more dramatic, but simply shows more clearly what we have also viewed in previous figures above; the majority of users are male subscribers and bikesharing is most often used during commute hours, especially evenings, and most especially - Thursday evening.
![Gender Weekday](https://user-images.githubusercontent.com/108022219/193721609-b4b7d857-677a-41e8-8745-77302039ab98.png)

These next 2 figures show the Top Starting and End points for users on a map. 
![Top Ending](https://user-images.githubusercontent.com/108022219/193721611-3a597ce3-c1d3-45c3-9e72-3dbd44f08de8.png)

![Top Starting](https://user-images.githubusercontent.com/108022219/193721614-270d155c-6e2c-48eb-8c29-2755b6eb64f8.png)

The last figure below highlights peak service times for all users. Peak user times are weekdays from 8-9am & 5-7pm, with two exceptions: Wednesday evenings are unusually slow, and Friday evenings end earlier.
![Weekday Per Hour](https://user-images.githubusercontent.com/108022219/193721615-0845ecd6-22ef-424e-ad37-d73614996efc.png)



## Summary
This analysis aimed to identify and visualize: the length of time that bikes are checked out for all riders and genders, the number of bike trips for all riders and genders for each hour and day of the week, and the number of bike trips for each type of rider and gender for each hour and day of the week.


Live visualization dashboards can be found at: https://public.tableau.com/views/NYCCitiBikeAnalysis_16644213323750/Story1?:language=en-US&:display_count=n&:origin=viz_share_link
