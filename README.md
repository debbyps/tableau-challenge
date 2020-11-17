tableau-challenge

Purpose: The purpose of this Tableau Challenge was to review the Citi Bike Trip History Logs and identify two unexpected phenomena.  Information needs to be aggregated and cleaned to appropriately visualize data. 

Data selected for analysis: It was decided to analyze bike trip history logs for summer 2019 and summer 2020 to see if there were any notable differences between the two summers. Data was combined using CMD prompts to copy/combine all CSV's of interest into one file.  It was imported into Tableau and filtered directly inside the data source to remove any outliers. 

Two dashboards were created to visualize the analysis of each phenomena described below:
1. Phenomena 1 - COVID Impact on User Type During Summer '19 & '20:
    There are two types of users that use Citi Bike's: Customers and Subscribers.  The first area to focus on was to see if there was a difference in the duration of the bike trips between the summer months for both years.  Ironically, it was clearly noticed that both customer types were taking longer trips. This trend suggests that users may have had more time to enjoy Citi Bikes around NYC despite COVID restrictions.

    Another interesting graphic showed that there was a swap between the number of trips taken by Subscribers vs Customers.  In 2019, Customer trips were lower than the ones they took in 2020.  Conversly, in 2019 Subscriber trips were higher than the ones they took in 2020. This pattern is difficult to correlate to COVID, however it is clear there was a shift.  Could it be that many users canceled their subscription due to the stay-home orders? Or did users select the wrong user type when checking out bikes? More analysis is necessary.

    Dashboard has filter options for end-user selection.

2. Phenomena 2 - COVID Impact on Rides per Day, Hour, and Gender During Summer '19 & '20:
    For this phenomena, we start with a weekday analysis of how mnay bike trips occurred on each day of the week and by each hour of the day.  It's interesting to see how much trips have decresed in 2020 during the peak hours of 6-10AM Monday - Friday!  There seems to be a solid correlations between this decrease and COVID restrictions as less people were commuting to work on those days.  Mornings on the weekend seem pretty much the same but afternoon trips had a notable uptick. 

    Lastly, there is a graphic to represent trips split by gender between both summers. It appears that in 2020 male rider ship was down, female was up and ridership of those who don't provide genders was also up.  It's diffcult to correlate this to COVID as it could just be a shift in the way users interact with the bike rental system.  It would be good to find some additional data to determine accuracy for at least the subscriber genders.

A story was created to show the visuals including the dashboards and one city map.  The city map was used to show the usage of bike ride start stations and it outlines the zipcode lines.  All ending points in New Jersy were excluded as the focus of ths analysis was trips in New York.  The marker size denotes the stations with higher usage as does the deeper blue.

Other graphics not included in story or dashboards: 
1. Top X Trip Start Stations - uses a parameter to have end-user input the top x start stations based on count bike    trips starting from that station. 

2. Bike End Station Usage - a map that shows the usage of end stations with a data layer by zipcode that shows the ratio of male/females.

