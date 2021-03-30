
# Data Sources

## Model for CO2 emission (Question 2)

Data used for predicting CO2 emission in model 2 can be found in UK_population.csv, GB_all_data.csv and data_quaterly.csv. While GB_all_data.csv was used to find best predictors, we used data_quaterly.csv to predict number of vehicles until 2030. Based on these, we use GB_all_data.csv, data_quaterly.csv and UK_population.csv to get the project of CO2 emissions.

Our sources came either from <a href = 'https://www.gov.uk/government/collections/vehicles-statistics' >UK Government data about vehicles</a> , <a href = 'https://naei.beis.gov.uk/data/data-selector'>National Atmospheric Emissions Inventory</a> and <a href = 'https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationprojections/bulletins/nationalpopulationprojections/2018based' >Office of National Statistics</a> . Please find exact details about source of each variable below, that includes either specific file name or filters used to extract the variables.

### GB_all_data.csv 

* *Total_CO2_kilotonne*   -  total_Vehicle_km * averageCO2 / 10^9 
* *Total_GHGs_kilotonne* -  Data from <a href = 'https://naei.beis.gov.uk/data/data-selector-results?q=142945'> NAEI </a> (category: cars , light duty tracs, heavy duty truck and buses, motorcycles, other road transport)  
* *Total_Cars* - VEH0101  
* *Total_ULEV_cars* - VEH0133  
* *Petrol* - VEH0203
* *Diesel* - VEH0203  
* *All_EV* -   ??????
* *All_ULEV_veh133*- VEH133  
* *ULEV_fraction* -   All_ULEV_veh133/Total_Cars
* *UK_population* - prediction taken from the <a href = 'https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationprojections/bulletins/nationalpopulationprojections/2018based' >Office of National Statistics</a> (data until 2019)
* *Total_Vehicle_km*- tra0201  
* *Average_CO2_(g-km)* - VEH0206
* *Average _CO2_cars_first_registered(g-km)* - VEH0156
* *Total_CO2_(NAE_data)*  - Data from <a href = 'https://naei.beis.gov.uk/data/data-selector-results?q=142224'> NAEI </a> (category: cars , light duty tracs, heavy duty truck and buses, motorcycles, other road transport)  

### data_quaterly.csv  

* *Cars* - VEH0101
* *LCV* - VEH0101
* *HGV* - VEH0101
* *Total* - VEH0101
* *All_ULEV_cars* - VEH133  
* *All_ULEV_vehicles* - VEH133  

### UK_population.csv

* *UK_population* - full prediction until 2043  taken from the <a href = 'https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationprojections/bulletins/nationalpopulationprojections/2018based' >Office of National Statistics</a>

## Scenario 1 (Social Awareness)

- uses Google trend data for differrent terms connected to the electric vehicles (the file [UK_pivotGoogle_orig.csv](UK_pivotGoogle_orig.csv)). The Google search trends can be downloaded here [https://trends.google.com/trends/?geo=US](https://trends.google.com/trends/?geo=US)

## Scenario 2 (Homeworking)
- Transport use during the coronavirus (COVID-19) pandemic : https://www.gov.uk/government/statistics/transport-use-during-the-coronavirus-covid-19-pandemic
- Daily Carbon emission https://carbonmonitor.org (data filtered for UK, for Ground Transport sector from 1st January 2019 to 31st December 2020)
- Homeworking, data from the Office of National Statistis: https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/conditionsanddiseases/bulletins/coronavirustheukeconomyandsocietyfasterindicators/1october2020#measuring-the-data
- Homeworking, data from EU Open Portal : https://data.europa.eu/euodp/en/data/dataset/orJJzGDF3cnXimvsoKDfXw (data is cleaned and filtered for emplyed people in UK in order to get a baseline of homewoking pre-covid times inside the scenario2 ipyb)

## Scenario 3 
- [market-share-of-electric-cars-in-norway](https://www.statista.com/statistics/1029909/market-share-of-electric-cars-in-norway/)




