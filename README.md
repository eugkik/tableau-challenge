# tableau-challenge

### **New Jersey CitiBike Distance and Duration Analysis** for 2018-2019

#### **Jupyter Notebook**

The *Tableau Challenge.ipynb* file was used to combine 24 months of New Jersey CitiBike data for 2018 and 2019.  Trips with a duration over 7 hours were considered outliers and removed from the dataset.  The combined data was exported as a CSV file for import into Tableau.

#### **Tableau**

Link to Tableau Public Visualization:

https://public.tableau.com/app/profile/eugene7493/viz/Tableau-Challenge_16382389676490/CitiStory?publish=yes

**Story Point 1** displays the total number of trips taken by CitiBike members and non-members during the two year timeframe, representing 10 times more members trips over non-members.  Also displayed are the distances, in miles, between the start and end station locations for each trip, calculated as the straight distance between the latitude and longitude coordinates for each station.

As expected, the *total* distance for member trips was substantially higher than non-members.  However, the *average* distance for each trip was higher for non-members.  For each day of the week, the average distance between start and end stations remained steady for members, while non-member distances were higher on weekdays and lower on weekends.

**Story Point 2** displays the average trip duration, in minutes, for each membership type.  It also displays the average trip duration by month over the two years.  The results show relatively steady durations, between 6 and 9 minutes, for members trips.  Non-member durations were three times higher, fluctuated between 17 and 30 minutes, increasing over the summer months and decreasing during winter months.

The data shows that the distance and duration for member trips remain steady throughout the days of the week, and month over month.  Non-member trips were longer and further than member trips, peaking during the weekdays and in summer months.

**Story Point 3** displays a dynamic map of New Jersery with each station plotted.  The size of the plot increases with the number of trip starts from that location.  A tooltip shows each station's name and the number of starts.  Using the time slider to change months shows the observed increase in trips during the summer, and the highest density of stations in the 07302 zip code.