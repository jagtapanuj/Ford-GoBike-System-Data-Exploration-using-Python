# (Dataset Exploration Title)
## by (your name here)


## Dataset

In the data, there are 183,412 trip records with 16 columns ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip').
The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).
Before starting the exploration some preliminary data wrangling was done like changing data types, deleting null value/useless records, adding new columns.

## Summary of Findings

After the exploration of this dataset, it was found that 97% of the trips are shorter than 1905 sec (or 31.75 mins). The usage of bikes is the result of office hour, i.e., more users use the bike around the start time and end time of the office hour. Weekend usage of bikes is almost half of that in the weekdays but users travel for longer duration during weekends. Males are the highest users of bike but they are they use it to travel for the least amount of time compared to other genders. Not many users do bike share but bike users who share bike are using it for longer duration and they are mainly customers and not subscribers. Longer durations trips occur after midnight (0th hour/12am) and before morning (around 4:30/5am).


## Key Insights for Presentation

For the [presentation](https://docs.google.com/presentation/d/1hEd45I0nJZZdUwJfhV-_aeyB4ZWE-vR5/edit?usp=sharing&ouid=103415477304732374828&rtpof=true&sd=true), I focued on:
- The time of day, day of week.
- Average trip duration
- Surprising fact that even though male are highest users, they don't travel for long durations.
- Finding out who does longer duration trips.