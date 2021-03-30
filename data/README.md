
# Data Sources

## Model in question 2

Data used for predicting CO2 emission in model 2 can be found in GB_all_data.csv and data_quaterly.csv. While GB_all_data.csv was used to find best predictors, we used data_quaterly.csv to predict number of vehicles until 2030. 

Our sources came either from government data about vehicles , National Atmospheric Emissions Inventory and…..population…. . Please find exact details about source of each variable below, that includes either specific file names or filters used to extract the variables.

### GB_all_data.csv 

* *Total_CO2_kilotonne*   - total_Vehicle_km*averageCO2/ 10^9  
* *Total_GHGs_kilotonne* -  NAE data https://naei.beis.gov.uk/data/data-selector-results?q=142224  
* *Total_Cars* - VEH0101  
* *Total_ULEV_cars* - VEH0133  
* *Petrol* - VEH0203: Licensed cars at the end of the year by propulsion / fuel type, Great Britain from 1994;  
* *Diesel* - VEH0203  
* *All_EV* -  
* *All_ULEV_veh133*- VEH133  
* *ULEV_fraction*  
* *UK_population *  
* *Total_Vehicle_km *- tra0201  
* *Average_CO2_(g-km)* - VEH0206: Licensed cars at the end of the year by CO2 emission and VED band 1, Great Britain from 2007;  
* *Average _CO2_cars_first_registered(g-km)* - Table VEH0156:Provisional 1 average reported CO2 emissions figure of cars registered for the first time by data source, monthly, Great Britain from January 2003;  
* *Total_CO2_(NAE_data)*  - Data from https://naei.beis.gov.uk/data/data-selector (category: cars , light duty tracs, heavy duty truck and buses, motorcycles, other road transport)  

### data_quaterly.csv  

* *Cars* - VEH0101
* *LCV* - VEH0101
* *HGV* - VEH0101
* *Total* - VEH0101
* *All_ULEV_cars* - VEH133  
* *All_ULEV_vehicles* - VEH133  
* *Greenhouse gas emissions from road transport*
* *Available Charging devices*
* *CO2 emmision: Cars*
* *Average CO2 first registered* - veh0156


## Scenario 1

- 

## Scenario 2 
- 


## Scenario 3
- 



---------- 

## GB all data:
https://www.gov.uk/government/collections/vehicles-statistics

- First 3 columns relate to CO2 emmision:
  - VEH0206: Licensed cars at the end of the year by CO2 emission and VED band 1, Great Britain from 2007;  
  - Table VEH0156:Provisional 1 average reported CO2 emissions figure of cars registered for the first time by data source, monthly, Great Britain from January 2003;
  - Data from https://naei.beis.gov.uk/data/data-selector (category: cars , light duty tracs, heavy duty truck and buses, motorcycles, other road transport)

- Next 10 columns are numbers of registed cars in GB
  - VEH0203: Licensed cars at the end of the year by propulsion / fuel type, Great Britain from 1994; 

- Last 5 columns relate to macro economic data

**UPDATE:**   
  
Total_Vehicle_km : tra0201  
averageCO2 (g/km) : veh0206  
total GHG: NAE data https://naei.beis.gov.uk/data/data-selector-results?q=142224  
total ulev: veh0133  
total cars: veh0101  
petrol and diesel:  veh0203  
total co2 (in kgt) is  total_Vehicle_km*averageCO2/ 10^9   

**quaterly data** 

total_ulev_cars : veh0133  
total_ulev_vehicles: veh0133  
Cars, LCV, HGV, total : veh0101  
Average CO2 first registered : veh0156  
