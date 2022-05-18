# Public Datasets for Production and Consumption
Here we store information on the public Datasets for Consumption and Production. These information are stored for AI4Energy. 

---------------------------------------------------------------------------------------------------------------------------------------------------

Table of Datasets available:


Name | Production | Consumption | Country | Prosumer Type | Data Type | RE Type | Battery | Time Resolution | Time Span | Status |  Additional Information
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
[Glava](https://github.com/AI-4-Energy/Dataset) | :white_check_mark: | :x:| Sweden | Industrial | CSV | Solar | :x: | 6s | 2015 - Today | Partly Open Source | 3 PV Grids
[Uppsala Energiporal](https://energiportalregionuppsala.se/open-data) | :white_check_mark: | :x:| Sweden | Residential + Non-Residential | JSON+CSV | Solar | :x: | 1, 5 Minutes or 1 Hour | 2019 - 2021 | Open Source | 17 Mixed (Residents + Industrial)
[Uppsala Tidunda](https://tinyurl.com/SchoolTiunda) | :white_check_mark: | :white_check_mark: | Sweden | Non-Residential | JSON+CSV | Solar | :white_check_mark: | 15 Minutes or 1 Hour | 2019 - 2021 | Open Source | 1 School
[Open Power System Data](https://data.open-power-system-data.org/household_data/2020-04-15) | :white_check_mark: | :white_check_mark: | Germany | Residential | CSV+SQLite | Solar + Wind | :x: | 1-15 Minute Resolution | 2014 - 2019 | Open Source | 11 Residents
[nrgyhub](https://nrgyhub.mdh.se/map) | :x: | :white_check_mark: | Sweden | Residential + Non-Residential | :x: | :x: | :x: | :x: | :x: | :x: | :x: 
Privat Dataset | :x: | :white_check_mark: | Sweden | Residential | CSV | :x: | :x:| Hourly | 2018 - 2019 | Private |  69 Residents




General Information
---------------------------------------------------------------------------------------------------------------------------------------------------

Here are some general information on the Datasets presented. 

Uppsala - Energiportal
---------------------------------------------------------------------------------------------------------------------------------------------------
This website has both, real time (API key necesarry?) and historical data from public PVs in Uppsala. Information on the houses etc. are here: https://energiportalregionuppsala.se/about. In total they promote 24 Prosumer there. Furthermore they have historical datasets publicly available: https://energiportalregionuppsala.se/open-data. 

They have either: separated information on each house / facility from 2019 - 2021, or combined information. Sadly they only provide the production side and NOT the consumption side. 

Additionally this site gives, as mentioned, singular information on for example Uppsala Tiunda School. In this case it provides the consumtion (15 Minutes interval): https://tinyurl.com/TiundaProduction and production (1 Hour Interval): https://tinyurl.com/TiundaConsumption.

---------------------------------------------------------------------------------------------------------------------------------------------------

Svensksolenergi
---------------------------------------------------------------------------------------------------------------------------------------------------

They provide PV Production from gigantic PV Parks (GWh), which is not applicable for our usecase: https://svensksolenergi.se/statistik/solkraft/. They also have the Data for multiple prosumer, but its private.

---------------------------------------------------------------------------------------------------------------------------------------------------
Open Power System Data
---------------------------------------------------------------------------------------------------------------------------------------------------

OPSD provides also two kinds of data. Firstly country-wise, which is not applicable. Secondy, they also have information on 11 Households in southern Germany in an hourly resolution: https://tinyurl.com/SouthGermanOPSD. 
