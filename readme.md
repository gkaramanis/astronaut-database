# Astronaut database

The data this week comes from [Mariya Stavnichuk and Tatsuya Corlett](https://data.mendeley.com/datasets/86tsnnbv2w/1). 

This [article](https://www.sciencedirect.com/science/article/abs/pii/S2214552420300444) talks about astronauts in greater detail.

This database contains publically available information about all astronauts who participated in space missions before 15 January 2020 collected from NASA, Roscosmos, and fun-made websites. The provided information includes full astronaut name, sex, date of birth, nationality, military status, a title and year of a selection program, and information about each mission completed by a particular astronaut such as a year, ascend and descend shuttle names, mission and extravehicular activity (EVAs) durations.

Credit: [Geoegios Karamanis](https://twitter.com/geokaramanis)

## Data dictionary

|variable                 |class     |
|:------------------------|:---------|
|id                       |double    |
|number                   |double    |
|nationwide_number        |double    |
|name                     |character |
|original_name            |character |
|sex                      |character |
|year_of_birth            |double    |
|nationality              |character |
|military_civilian        |character |
|selection                |character |
|year_of_selection        |double    |
|mission_number           |double    |
|total_number_of_missions |double    |
|occupation               |character |
|year_of_mission          |double    |
|mission_title            |character |
|ascend_shuttle           |character |
|in_orbit                 |character |
|descend_shuttle          |character |
|hours_mission            |double    |
|total_hrs_sum            |double    |
|field21                  |double    |
|eva_hrs_mission          |double    |
|total_eva_hrs            |double    |