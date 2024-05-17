ABOUT THE PROJECT: This is a group project in a programming course where we aimed to discover any possible relations between bike usage and population distribution in Helsinki and Espoo through visualising data using Python. 

MOTIVATION: HSL provides bike services for Helsinki and Espoo, but the services are still limited. Therefore, we would like to examine the pattern of bikes usage in Helsinki and Espoo and recommend which regions HSL should build more bike stations.

PRELIMINARY ASSUMPTIONS:
- Area-specific population is correlated with total cycling distance and total cycling duration.
- Age group is correlated with geographical population distribution.
- Younger people live near the center than older people.

DATASETS:
- Main dataset:
File: hsl_main_dataset.csv (This file is not uploaded because of its large size but can be easily obtained from HSL website.)
Description: information about HSL's bike stations name, the covered distance and covered duration of each route
Note: in this project, we use the term "route" to refer a pair of 2 stations

- Additional dataset:
-   File: Espoo_additional_dataset.cs
  Description: Population statistic of Espoo

  File: Helsinki_additional_dataset.csv
  Description: Population statistic of Helsinki

  File: latitude_longitude_additional_dataset.csv
  Description: Population statistic of Espoo

  File: latitude_longitude_additional_dataset.csv
  Description: The geographical latitude and longitude of each sub-regions in Helsinki and Espoo. This is obtained by using the Google Map API (see the section 2)

  File: station_area_additional_dataset.csv
  Description: The data mapping between the station names and sub-region names. This is obtain by using Google Map API and mappping the geographical information (see the section 2)
