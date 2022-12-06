# Bikesharing
Visualizing bike-sharing data with Tableau.

## Overview
Analyzing New York City bike-sharing data from August 2019, and evaluating the plausibility of a similar bike-sharing service in Des Moines, Iowa.
#### Resources:
* 201908-citibike-tripdata.csv
* NYC_CitiBike_Challenge.csv
<br></br>

## Results
[View Story on Tableau Public](https://public.tableau.com/views/NYC_Bikesharing_Challenge/NYCCitiBikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### Popular Ride Times
![All Trip Start Times](./Resources/When-Do-People-CitiBike.png)

### Trip Durations
![All Trip Durations](./Resources/All-Checkout-Times.png)

These first two charts give us insight into why people are using CitiBike. They don't spell it out for us, but they both seem to point toward commuting and weekend leisure.<br></br>
The first chart is a heatmap highlighting the most popular times for CitiBike rides, typically morning/evening rush hour. The second chart tells us how many rides there were for every possible trip duration (in minutes). We know then that most bikes are used during the morning/evening rush for about 3-8 minutes which - in New York City - probably gets you close to your destination. We also know that on weekends bikes are mostly used during the day. Users are likely running errands and want to get around quickly without the hassle of the subway or a cab. But who are these users?


### Who uses CitiBike?
![User Breakdown](./Resources/Who-Uses-CitiBike.png)

With more than 80% of business coming from subscribers, the service seems most popular with those who use CitiBike regularly, which is promising. This means business is regular and stable rather than sporadic. It is certainly a product of the demographic, as urban commuters foster high demand for public transport, but it also indicates CitiBike is of a high enough quality and reliability to retain a large portion of its customers, which is important in any venture.

Additionally, over 65% of users are male - most of whom are subscribers as well. Let's expand on that...
<br></br>

## Results by Gender
### Popular Ride Times by Gender
![Trip Start Times by Gender](./Resources/When-by-Gender.png)

### Trip Durations by Gender
![Trip Durations by Gender](./Resources/TripDurations-by-Gender.png)

The visualizations above are nearly identical to the first two, as the patterns are the same in both sets of images. All three heat maps here are the same as the first, and this line chart looks like one from earlier as well. Clearly the only difference is the division of each chart by gender, which has magnified the weight each carries in the overall data from before.<br></br>
We can determine that everyone is using the bikes around the same times, and for the same amounts of time, regardless of gender. That said, men are using the bikes the most frequently. There is some popularity with women as well, but based on the Trip Durations by Gender chart, males are using the service nearly three times more than anyone else.<br></br>
What does this mean for Des Moines? Well, it could mean that CitiBike is most popular with men who are looking to stay fit and get around town easily. Based on the data there are women who fall into this category as well, just fewer. In that case, the city of Des Moines should market the bikes to these commuters, who are probably nimble young people, but should still promote bike use among other demographics. Sure, in New York the bikes are mostly used in the mornings and evenings, but people work during the day, so there will always be less people on the road (or sidewalk). The service can be used for a number of reasons, including shopping, travelling, exercise, etc., and I think the all-day all-gender popularity of the bikes on Fridays, Saturdays, and Sundays, should prove it.

<br></br>

## Summary
In short, the service can be marketed in a variety of ways, from a fit- and environmentally-friendly way to commute, to cheap and readily available public transport, or even as a weekend leisure activity. Its appeal to a number of demographics (thanks to its versatility) alongside its exceptional customer retention indicate a high probability for success in other cities.<br></br>
Obviously Des Moines is less populous than New York City, and by no small margin, but it is still a highly populated area with an untapped customer base. The numbers might be smaller than New York's, but there is no evidence the proportional data should widely vary. The appeal is the same, there are just less people.<br></br>
That said, more research could further explain CitiBike's success in New York City, and help assess its prospects in Des Moines more accurately. More user data could tell us which age groups it is most popular with, distances travelled, trip durations by weekday by hour, etc. While it is hard to doubt CitiBike's plausibility in any city, such data would provide a tremendous advantage in marketing and deployment, giving it a greater chance of success in Des Moines.
<br></br>

[View Story on Tableau Public](https://public.tableau.com/views/NYC_Bikesharing_Challenge/NYCCitiBikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
