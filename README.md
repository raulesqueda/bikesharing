# bikesharing

## Overview of the statistical analysis:

### The purpose of the analysis:
Using the skills we learn for Tableau, now we are going to create a story to convince the investors that a bike-sharing program in Des Moines is a solid business proposal, for this we are going to show to one of the key stakeholders our bike trip analysis.

In this analysis, we used Jupyter Notebooks to change the "tripduration" column from an integer to a datetime datatype. Then, we use the data in Tableau to create several visualizations:
1.	The length of time that bikes are checked out for all riders and genders
2.	The number of bike trips for all riders and genders for each hour of each day of the week
3.	The number of bike trips for each type of user and gender for each day of the week.

Now that we got all the graphs, we built a story inside Tableau for the presentation. In the next section, we resume the main results of the visualizations and the story for the stakeholders.

### Results:
For the bike-sharing program in Des Moines, we use the information of Citibike of NYC, the first thing we want to know is the length in minutes of the rides, for the rides in NYC, the maximum peak where 5 minutes, but we get long rides as more than 60 minutes.
![Graph 1](https://github.com/raulesqueda/bikesharing/blob/main/Images/graph1.PNG)
Now we want to know the gender of the riders, most of the riders are male, followed by female riders. By gender, the length of the rides has the same trend as we saw before:
![Graph 2](https://github.com/raulesqueda/bikesharing/blob/main/Images/graph2.PNG) 
Now we want to know the peak hours of usage of the Citibike system, per weekday and hour, we can see that from Monday to Friday, the peak hours are from 8 am to 9 am and from 5pm to 7pm, for Saturday and Sunday we saw a different behavior and it is less used by the riders:
![Graph 3](https://github.com/raulesqueda/bikesharing/blob/main/Images/graph3.PNG) 
By gender and weekday and hour, we can see the same trend in terms of hours by female and male riders, as we saw before, most of the riders are male:
![Graph 4](https://github.com/raulesqueda/bikesharing/blob/main/Images/graph4.PNG) 
Finally, we want to know by user type the weekday of use and gender, we can see that we have more subscribers than customers, but the male riders are more than the female riders, and the trend we saw in terms of weekdays are the same:
![Graph 5](https://github.com/raulesqueda/bikesharing/blob/main/Images/graph5.PNG) 

### Summary:
As we saw in the data, most of the users are **male riders that uses the Citibike system from Monday to Friday in different hours, but mostly between 8am to 9 am and 5pm to 7pm**. This information is crucial for the business project for Des Moines, we could start developing a marketing strategy for this group of people and then continue with the female riders.

To have more information about the system, maybe we can get data about the average distance of the trips, this for the bike stations localizations in Des Moines, and weather information, we want to know if weather time had effects in the usage of the bike system.

The dashoboard is available here in [Tableau Public](https://public.tableau.com/app/profile/ra.l.esqueda.mart.nez/viz/Module14_challenge_16647448531910/Historia1?publish=yes)
