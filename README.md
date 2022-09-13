# Bikesharing

## [Link to Visualization](https://public.tableau.com/app/profile/snehal.desavale/viz/Bikesharing_Challenge_16630415857090/Bikesharing_story?publish=yes)

## Overview of the analysis: Explain the purpose of this analysis.
Create a story to convince the investors the bike-sharing program in Des Moines is a solid business proposal
For this analysis, Pandas needs to use to to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, create a set of visualizations to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

Final story will contain above visualizations as well as 2 visualizations which created in module.

## Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.
### Deliverable 1: Change Trip Duration to a Datetime Format
Following image shows the changed format of tripduration column.
<img width="1576" alt="tripduration column" src="https://user-images.githubusercontent.com/106944351/189739758-4142dc4b-995a-4c16-bad2-9bcf8e25672a.png">

### Deliverable 2: Create Visualizations for the Trip Analysis
1) Number of Trips - There are multiple people using bikes everyday. This is the number of August trips.
<img width="321" alt="Number of trips" src="https://user-images.githubusercontent.com/106944351/189739818-ba70a7cc-8c95-4c03-80b7-9405348db9d6.png">


2) Gender Breakdown - This graph shows usage of bikes by Males and Females.
<img width="1289" alt="Gender Breakdown" src="https://user-images.githubusercontent.com/106944351/189813186-4e9e89ec-0271-4df2-9ddd-7a9e77e28945.png">


3) Checkout Times for Users - This graph shows checkout times for users
<img width="1300" alt="Checkout Times for Users" src="https://user-images.githubusercontent.com/106944351/189740101-afd183eb-4324-4dbd-ae36-9c4ab731410e.png">


4) Checkout Times by Gender - Males are using the bike facility more as compared to females.
<img width="1299" alt="Checkout Times by Gender" src="https://user-images.githubusercontent.com/106944351/189740125-6a55e6fc-e8a0-4f59-976f-4af96735d484.png">


5) Trips by Weekday for each Hour - People prefer biking early morning between 6AM - 9AM and in the evening 4 PM-8 PM. As compared to morning,  evening seems like a rush time for biking regardless of which day it is. We get plenty of time to repair the bikes When the demand is less such as after 12 AM until 4 AM or maybe in the afternoon.
<img width="1291" alt="Trips by Weekday for each Hour" src="https://user-images.githubusercontent.com/106944351/189740166-5a4874a4-73d3-4a9e-8610-3db2f1bdcd0e.png">

6) Trips by Gender (Weekday per hour) - The graph shows obvious finding that male population is using bikes more than females regardless of what day it is.
<img width="1298" alt="Trips by Gender (Weekday per hour)" src="https://user-images.githubusercontent.com/106944351/189740181-6e326752-fc17-441e-99f7-899a32794f48.png">


7) Trips by Gender by Weekday by user - The subscribers are using bikes on daily basis as compared to random customers.
<img width="467" alt="User Trips by Gender by Weekday" src="https://user-images.githubusercontent.com/106944351/189740215-dadaf8ea-945a-46d1-a342-3ad74b79bced.png">

8) Top Starting Locations-
<img width="1300" alt="Top Starting Locations" src="https://user-images.githubusercontent.com/106944351/189816543-3b171fab-797f-472a-98f1-5c78e7b0b63a.png">

9) Top Ending Locations -
<img width="1279" alt="Top Ending Location" src="https://user-images.githubusercontent.com/106944351/189816579-5bdb181f-2d48-4eb8-ba23-23bc1142b0a8.png">



### Deliverable 3: Create a Story and Report for the Final Presentation
Story also includes visualization of number of rides, pie chart of gender breakdown, top starting locations and top ending locations from the module.

## Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.
- The usage of bike in metropolitan areas is remarkably impressive. The lack of parking space for cars due to lot of buildings is encouraging customers to take advantage of the facility. The reliable customers base is male as compared to female but some of the schemes we can start to attract female customers.
- The numbers of bikes can be made available at certain rush hours or at certain famous locations. 

- Additional Visualizations -
1) Average trip duration, by birth year, by gender, to find out if there was any difference in male or female or un-gendered riders as they age.

2) Considering famous starting and ending locations, how many males and females are using this service.




