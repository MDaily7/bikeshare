# Tableau with bikesharing
## Overview
The purpose of this project was to gain experience with Tableau by generating several visuals and a storyboard with New York City bikeshare data. The proposed scenario is
that these visualizations would be used as a case to investors for a bikeshare in another city. Most visualizations were created directly from the downloaded dataset with two 
exceptions. The gender data had to be altered with a calculated field in Tableau so that the numerical representations were converted to their respective genders. 
In addition to this, the tripduration was converted from an integer to datetime format using Pandas to_datetime function, and the converted values were saved into a new 
column (converted tripduration). 
## Results
* [Checkout Times for Users](https://github.com/MDaily7/bikeshare/blob/main/Images/Checkout_Times_for_User.png) displays the trip duration for each use of a bike. Most trips are five to six minutes long.
* [Checkout Times by Gender](https://github.com/MDaily7/bikeshare/blob/main/Images/Checkout_Times_by_Gender.png) breaksdown the checkout times by each gender. Most bikes are checked out by men and usually for about five minutes whereas women typically
checked out bikes for six minutes. 
* [Use Times](https://github.com/MDaily7/bikeshare/blob/main/Images/Peak_Hours.png) are illustrated by two visualizations. The first is a heatmap showing that the peak hours are about 8am and 6pm with a decent amount of usage between those 
hours. There is more usage between those hours on the weekend. The bar graph further illustrates the peak hours are generally 8am and 6pm. 
* [Use Times by Gender](https://github.com/MDaily7/bikeshare/blob/main/Images/Trips_by_Gender_Heatmap.PNG) Shows that men and women are generally using bikes at around the same times. Men use them more, and will use them later then women generally do, 
but a fair amount of usage hours overlap. 
* [Use by User type and Gender](https://github.com/MDaily7/bikeshare/blob/main/Images/User_Trips_by_Gender.PNG) Continues to display that men are using the bikes more. Additionally, this figure shows that subscribers are using the bikes far more than
non-subscribers. 
* [Gender Breakdown](https://github.com/MDaily7/bikeshare/blob/main/Images/Gender_Breakdown.PNG) is a pie chart illustrating that the user base is predominately male. 
* [Bike Utilization](https://github.com/MDaily7/bikeshare/blob/main/Images/Bike_Utilization.PNG) shows the total tripduration for each bikeid for all of the uses of the bike. Circle size increases as the sum of trip duration increases. 
## Summary
Looking at the various visualizations, it is clear that men are the predominate users of the bikeshare. Additionally, peak hours tend to be before and after standard work 
hours during the week. Whereas, on the weekends, usage is more evenly distributed likely becuase fewer people are working. A small portion of bikes are used far more than 
others; this is likely due to the location of where those bikes reside. It may be beneficial to rotate where bikes are located to further reduce the amount of bike repairs
that are required or to increase the number of bikes at the locations where bikes are being used most. Additional visualizations could include breakdowns by age. For example,
the average trip duration by age, the gender breakdown distributed by age, the average amount of usage by age, and the ages of subscribers compared to non-subscribers could 
all be useful aspects of the data to illustrate. In the proposed scenario where this data is being used as a pitch to investors for a bikeshare in a new city, it would be 
useful to include displays about the demographics of the new city that provide confidence that the results seen here are translatable to the new city. For example, if the 
average amount of use by age indicates that people in their forties do not use the bikeshare much and the new city is largely populated by people in their forties, this 
would be an important detail to share with investors. 
## Resources
* [Images](https://github.com/MDaily7/bikeshare/tree/main/Images)
* [Data Source](https://www.citibikenyc.com/system-data), the 201908-citibike-tripdata.csv was used in this project
* [Jupyter Notebook](https://github.com/MDaily7/bikeshare/blob/main/Resources/NYC_Citibike_Challenge.ipynb) used to convert the tripduration into datetime 
* [Tableau Public Link](https://public.tableau.com/app/profile/michael2532/viz/NYC_Citibike_Challenge_Dashboard/BikeShareStory?publish=yes)
