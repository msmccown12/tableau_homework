# tableau_homework

Citi Bike Program Investigation 

After reading about the CitiBike Program and seeing the data we had access to, I decided to investigate the effects of COVID on the CityBike program.  
To do so, I looked into the data for all of 2019 and 2020. I combined all 24 months of data into a CSV to load into Tableau. 

To start my investigation, I used Tableau to do general Exploratory Data Analysis to look into the data that existed. I extracted different date fields from the start 
date including the year, year and month, year month and data -- to separate the data into slices to analysis and use in the visualizations. This included looking at 
time series data - the count of bike rides, trip duration total and average, and more over time from January 2019 to December 2020.  I also looked at the frequency the 
start and end stations were used for trip rides.  Lastly, I looked into the demographics of the trip rides and trip duration. 

There seemed to be a dip in the early months of 2020 when COVID and the quarantine first started.  Even with the dip in the early months, the average trip duration 
gradually increased and was at its highest in the summer of 2020.  The rise in the trip duration was a phenomenon I wanted to look more into.  

Trip Duration 

The trip duration gradually increases in the spring of 2020 and stays higher for the rest of the year compared to 2020. 
I then dove further into additional slices of the data-  

I looked at the customer user type and gender in regards to the total trip duration (sum) and the average trip duration. The highest total trip duration group was 
the male subscribers. 2nd highest was the unknown customers.  The highest average trip duration was the unknown customers followed closely behind by the 
female customers.  

I also redid the time series graph to include a slice for user type and one for gender.  All of these graphs are located on the dashboard. 

Citi Bike Program Users by Birth Year 

I was surprised to see some spikes in the data which looking at ride count and trip duration in regards to birth year of the user.  

We see a normal distribution in the ride count of users from about 1970 on.  We don't see as much of a regular distribution when looking at trip duration. 

In reference to total trip duration, there is a spike in the year 1969 -- so I looked more into the demographics and found a large number of unknown gender customers 
with that birth year. 
 
Similarly, there is a spike in 1939 when looking at average trip duration (instead of total) -- I looked into those demographics and only male customer is a part of 
this spike. 

Location of Start Stations and End Stations 

On the next page, you can find the zip code designations in a map of the start and end locations. The size of the dot on the map refers to the bike count.  
The color responds to the average in trip duration for that station. 
