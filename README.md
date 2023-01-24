# NYC-Bike-Sharing
An analysis of NYC CitiBike bikesharing data from August, 2019, with Tableau
## Overview
The framework for this project is data from CitiBike in New York City for presentation to investors looking to begin a bike-share program in Des Moines, Iowa. While Des Moines is a long way away from the hustle and bustle of NYC, this analysis might help answer a few key questions:
1. Who uses this program?
2. What area of a city is seen the most through bike-share usage
3. What time of day are bikes used the most and least
4. How much are bikes used and by whom?
## Results
While the demographics of Des Moines differ from the makeup of the citizenry of NYC, an overlook of CitiBike riders shines a light on who bike-share might appeal to, regardless of locale.

<img width="540" alt="nycCB_cust_descrip" src="https://user-images.githubusercontent.com/113754027/214232316-7796526f-eb40-47e5-b80c-15951683511c.png">
In the above image, we can see that more than 3/4 of the users are Subscribers who make regular use of the bikes and are a great source of income for the program. Bikeshare program users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared. 

<img width="797" alt="nycCB_start_loc" src="https://user-images.githubusercontent.com/113754027/214232542-d08e8031-2956-47fe-aac1-e5ad50c1e25e.png">
The above map displays the bike stations from which recorded bike trips started. The circles' size and the green's darkness indicate the relative number of trips started at those locations. Most bike trips originate in the bustling commercial heart of Lower Manhattan, known for towering office buildings, densely packed residential skyscrapers, and entertainment venues. Consequently, bike usage is lower in the less densely packed surrounding neighborhoods. 

<img width="880" alt="nycCB_repair_time" src="https://user-images.githubusercontent.com/113754027/214232904-0c49b31b-8749-4597-b14a-2a01fd050841.png">
This chart displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August. We can see peak usage during morning rush hour and end-of-workday commute times. Also of note is the low-usage hours between 2 AM and 5 AM. These hours would be the best times to start bike repairs and redistribute bikes from total stations to less-full stations.  

<img width="521" alt="nycCB_peak_use_hours" src="https://user-images.githubusercontent.com/113754027/214233142-56ffd050-173e-4327-857a-96afe9f57bdc.png">
A heatmap also helps show weekly usage patterns. Once again, we can see heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. The relatively low bike usage during Wednesday's end-of-day commute is an interesting anomaly. It could be helpful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours every day of the week. 

<img width="982" alt="nycCB_usage_spread" src="https://user-images.githubusercontent.com/113754027/214233372-2e22c8e2-9972-402f-a0e8-22493406da34.png">
To see what proportion of the bikes get heavy usage, we can look at this stepped-level heatmap. This tiling shows each cycle in the fleet, sized, colored, and sorted by its degree of usage during the month. In red, we can see a small number of bikes that get heavy use, which will require more regular repair or possibly even replacement. In shades of green, we can see all the other bikes that get much lower levels of use and will probably not need to be repaired as often. 

![nycCB_avg_tripdur_birthyr](https://user-images.githubusercontent.com/113754027/214233552-3e08aca1-0217-4728-a1b2-7557266997de.png)
This charting of average trip duration by birth year shows two things:

1. The bike-share userbase covers all age demographics, from teenagers to nonagenarians (and older);
2. Teenagers and early-twenty-somethings enjoy taking much longer bike rides than older users.

<img width="972" alt="nycCB_trip_duration" src="https://user-images.githubusercontent.com/113754027/214233976-52c35501-b1e4-4bd2-8317-2e4388304803.png">
This graph of the number of trips by duration shows that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour, with a swift number of rides over an hour. 

<img width="972" alt="nycCB_trip_duration_gender" src="https://user-images.githubusercontent.com/113754027/214234163-d19d75ca-68ee-480b-9ba3-e0e7172625af.png">
This breakdown of the number of rides by duration, separated by gender, makes it even more apparent how many more passages are taken by male-identifying customers. 

![nycCB_trips_user_day_gender](https://user-images.githubusercontent.com/113754027/214234281-62a483b8-f1b9-4471-b839-9526dcd1f9de.png)
Lastly, this heatmap reinforces how much of the user base is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.
## Summary
In conclusion, bike share services are top-rated in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. In addition, the user base is primarily male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem to be a reliable market. And the primary usage focuses on morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore the following:

-Trip starting and ending locations during morning and evening rush hour time-windows to display the flow of traffic between neighborhoods at peak hours;
-Average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they aged.
