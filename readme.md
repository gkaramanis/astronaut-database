# Astronaut database

The data this week comes from [Mariya Stavnichuk and Tatsuya Corlett](https://data.mendeley.com/datasets/86tsnnbv2w/1). 

This [article](https://www.sciencedirect.com/science/article/abs/pii/S2214552420300444) talks about astronauts in greater detail.

This database contains publically available information about all astronauts who participated in space missions before 15 January 2020 collected from NASA, Roscosmos, and fun-made websites. The provided information includes full astronaut name, sex, date of birth, nationality, military status, a title and year of a selection program, and information about each mission completed by a particular astronaut such as a year, ascend and descend shuttle names, mission and extravehicular activity (EVAs) durations.

Credit: [Geoegios Karamanis](https://twitter.com/geokaramanis)

## Data dictionary

| variable                 | class     | description                                               |
| :----------------------- | :-------- | --------------------------------------------------------- |
| id                       | double    |                                                           |
| number                   | double    |                                                           |
| nationwide_number        | double    |                                                           |
| name                     | character | Full  name                                                |
| original_name            | character | Name in original language                                 |
| sex                      | character | Sex                                                       |
| year_of_birth            | double    | Year of birth                                             |
| nationality              | character | Nationality                                               |
| military_civilian        | character | Military status                                           |
| selection                | character | Name of selection program                                 |
| year_of_selection        | double    | Year of selection program                                 |
| mission_number           | double    | Mission number                                            |
| total_number_of_missions | double    | Total number of missions                                  |
| occupation               | character | Occupation                                                |
| year_of_mission          | double    | Mission year                                              |
| mission_title            | character | Mission title                                             |
| ascend_shuttle           | character | Name of ascent shuttle                                    |
| in_orbit                 | character |                                                           |
| descend_shuttle          | character | Name of descent shuttle                                   |
| hours_mission            | double    | Duration of mission in hours                              |
| total_hrs_sum            | double    | Total duration of all missions in hours                   |
| field21                  | double    |                                                           |
| eva_hrs_mission          | double    | Duration of extravehicular activities  during the mission |
| total_eva_hrs            | double    | Total duration of all extravehicular activities in hours  |