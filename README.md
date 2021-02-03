# Ford GoBike Data Exploration

## Dataset

The dataset is for all trips taken during February of 2019, with 16 features recorded, including: the duration, start and end time, start and end station plus their coordinates, user birth year, user gender, etc.. and 183412 records.


## Summary of Findings

In the exploration, I found that the hours of the start and end of the work day have the highest activity on the service. In addition, it was also noticeable how the start hour of the day would impact the duration of the trip. While observing more relationships between features and the trip duration, I found that the mean duration of the trip is the highest for trips that start around 3am, reaching above the 1400 second mark. As for the trips that start around 6am, it has the lowest mean duration. Same goes for the end hour of the trip, still following the same pattern. On another note, we did not notice any trip durations higher than 20000 seconds for users who were born earlier than 1960. Consequentially, we see more outliers of duration for younger users. Another key finding is that we found that the median trip duration for all genders to be almost the exact same, with the same interquartile ranges and outliers. However, this changed when comparing use types for the service, as customers had a higher median trip duration than subscribers.


## Key Insights for Presentation

For the presentation, I start with presenting a general understanding of the demographic of the users, showing the proportion of each gender, the proportion of user types, the distribution of the generations, start hour of the day, and the distribution of the log scale transformed trip duration. Afterwards I showed the relationship between each of these variables and the trip duration. All while keeping the figures simple and understandable for the average reader. The figures highlight the trends of the users in terms of trip duration. It also highlights which segment of the users, at what time of the day, have the highest trip durations. Then I went on to present slightly more complex relationships, highlighting the relationships between two variables and their effect on the trip duration.
