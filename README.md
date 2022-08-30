# bikesharing
# Module 14: NY Citibike with Tableau

## Overview of the statistical analysis:

## The purpose of the analysis is well defined.

To convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, using Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, create a set of visualizations to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.
- Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

### Deliverable 1: Change Trip Duration to a Datetime Format
- The data in the "tripduration" column is converted to a datetime datatype and has the correct time format
- The DataFrame is exported as a new file without the index column

### Deliverable 2: Create Visualizations for the Trip Analysis
- There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour
- There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender
- A heatmap is created showing the number of bike trips for each hour of each day of the week
- A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender
- A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender

### Deliverable 3: Create a Story in Tableau
![Tableau_Story](https://public.tableau.com/app/profile/veena.puvvada/viz/citibike_challenge_16613887111010/Story1?publish=yes)

## Results:

- There are more male users than female and unknown users.
- Most weekday rides are between 7:00 am to 9:00 am in the morning and between 4:00 pm to 7:00 pm

Here are the visualizations for the NYC Citibike analysis

![citibike_data](https://github.com/veenapu/sharing_bikes_challenge/blob/main/Images/citibike_data.PNG)
Here is the citi bike data with the trip duration column with added datetime stamp.

![Number_of_Records](https://github.com/veenapu/sharing_bikes_challenge/blob/main/Images/No_of_records.PNG)
The number of records analyzed are 2,344,224.

![Gender_breakdown](https://github.com/veenapu/sharing_bikes_challenge/blob/main/Images/Gender_breakdown.PNG)
Highest bike user pecentage was male (65%), then female (25%) and then unknown(10%). 

![Checkout_Times_for_Users](https://github.com/veenapu/sharing_bikes_challenge/blob/main/Images/Checkout_Times_for_Users.PNG)
Most bikes checked out for 4-6 hours.

![Checkout_Times_by_Gender](https://github.com/veenapu/sharing_bikes_challenge/blob/main/Images/Checkout_Times_by_Gender.PNG)
There were 3 times more male bike users than female bike users.

![Trips_by_Weekday_per_hour](https://github.com/veenapu/sharing_bikes_challenge/blob/main/Images/Trips_by_Weekday_per_hour.PNG)

![Trips_by_Gender](https://github.com/veenapu/sharing_bikes_challenge/blob/main/Images/Trips_by_Gender.PNG)

![User_Trips_by_Gender_by_Weekday](https://github.com/veenapu/sharing_bikes_challenge/blob/main/Images/User_Trips_by_Gender_by_Weekday.PNG)

- Most weekday rides are during rush hours between 7 am to 9 am and 5 pm to 7pm.
- Weekend rides are highest from 10 am to 7pm.
- Those rides are mostly taken by male bike users.

## Summary:
The analysis shows high activity in New York in the month of Aug. 2019.  Most rides are taken by male users during rush hour in the morning and evening. This is probably due to the fact the bike service is used as an alternative to the public transportation.

Additional analysis can be done on analyzing for different months to see a pattern/trend to increase the bike usage.  And, weather can play a key factor in finding the correlation between the bike usage and weather.


